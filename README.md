# archiveurl
Archive a URL in Internet Archive's [Wayback Machine](https://archive.org/web/).

## Usage
Multiple URLs (one per line) can be provided,
e.g. piping: 'cat urls.txt | archiveurl'

You may use this script together with "[geturls]"[1] to automatically archive all links insed a web page,
e.g. 'geturls https://www.openbookpublishers.com/htmlreader/978-1-78374-323-0/main.html | archiveurl'

You may specify a list of URLs that should not be archived, either using the def
ault file './exceptions.txt' or through env vars: `export EXCEPTION_FILE=/path`.

[1]: https://github.com/OpenBookPublishers/geturls
