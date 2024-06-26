Configuration for [WRS](https://en.wikipedia.org/wiki/User:Syced/Wikipedia_Reference_Search), the search engine that aims to only return results from reliable websites.

# How to contribute

1. Download annotations.xml.
2. Edit it via in a simple text editor. For instance:
  - Remove a line.
  - Add a line by copy/pasting an existing line.
  - Even if you do not know XML, do not worry: The only parts to touch are the URL and the include/exclude keyword.
3. Make sure the XML file is still valid, using a validator such as https://www.xmlvalidation.com.
4. Send a [GitHub pull request](https://help.github.com/en/articles/creating-a-pull-request).

If you add websites, be sure that they comply with https://en.wikipedia.org/wiki/Wikipedia:Reliable_sources.

The limit is 5000 sites, we are currently far from it.

Do not hesitate to send pull requests for other improvements, all of the search engine's configuration is in context.xml.

Thanks!

# Notes for the maintainer
After accepting each GitHub pull request:

1. Go to https://cse.google.com.
2. Click on "Wikipedia Reference Search".
3. Delete all sites from both `Sites to search` and `Sites to exclude` (deletion takes a minute for each page of 100 sites so that takes a rather long time).
4. Open "Upload/Download Annotations in XML files".
5. Upload the new file.
