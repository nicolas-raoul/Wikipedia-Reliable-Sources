Configuration for [WRS](https://en.wikipedia.org/wiki/User:Syced/Wikipedia_Reference_Search), the search engine that aims to only return results from reliable websites.

# How to contribute

1. Download annotations.tsv
2. Edit it via in your favorite spreadsheet program (for instance Libre Office, free)
3. Send a [GitHub pull request](https://help.github.com/en/articles/creating-a-pull-request)

If you add websites, be sure that they comply with https://en.wikipedia.org/wiki/Wikipedia:Reliable_sources

Thanks!

# Notes for the maintainer
After accepting each GitHub pull request:

1. Update local Git repository with "git pull"
2. Go to https://cse.google.com
3. Click on "Wikipedia Reference Search" > "Advanced" > "CSE Annotations"
4. Select the existing TSV and press "Delete"
4. Press "Add" and select the new TSV file
