# scraper

A scraper for Jom Belajar Java wordpress blog. The scraped files can be seen [here](https://github.com/JomBelajarJava/old-content).

### Usage

Load scraper:

```
$ sbcl --load scraper.lisp
```

Scrape:

```
$ (scrape-all)
```

The output will be inside `out` folder.
