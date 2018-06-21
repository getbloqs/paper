# Whitepaper - Documentation

## AsciiDoc

This paper is written with AsciiDoc. AsciiDoc has the great advantage to build various output formats (e.g. pdf, epub, html, ...) from the input sources. In order to build the output formats AsciiDoc has to be installed first. Therefore you can go through the linked [installation guidelines](https://asciidoctor.org/docs/user-manual/#getting-started).

## Build the document

The html representation of the document can be build with the following command:
```
asciidoctor -d book -a lang=de -D build paper.asciidoc
```

The pdf representation of the document can be build with the following command:
```
asciidoctor -r asciidoctor-pdf -b pdf -d book -a lang=de -D build paper.asciidoc
```
