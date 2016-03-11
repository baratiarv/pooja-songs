# Markdown source for Pooja Songs #

## Description ##

This is a markdown version source of Pooja songs ebook

## Prerequisites

- [Pandoc](http://pandoc.org/)

## Building ##

Build the ebook using the following command

``` sh
$ pandoc -S -o pooja.epub title.txt 01-ganesha-pancharatnam/01-chapter1.markdown \
	02-vishnu-sahasranamam/02-chapter2.markdown \
	03-mahalakshmi-ashtakam/03-chapter3.markdown \
	04-sri-hanuman-chalisa/04-chapter4.markdown \
	05-lingashtakam/05-chapter5.markdown
```


