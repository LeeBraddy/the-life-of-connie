# E-Book Project

## Build HTML and EPub

    pandoc -d defaults.yaml -d html.yaml
    pandoc -d defaults.yaml -d epub.yaml

## Images

Cover image dimensions should have a portrait layout.

* Kindle Direct Publishing: 1:1.6, ideal width 1600px
* Kindle Page Display: 1:1.5, ideal width 2500px

I'm using 1:1.5 with 2500px width for the cover.jpg
and 1024px width for all other images.
