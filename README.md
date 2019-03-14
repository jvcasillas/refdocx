# refdocx

Pandoc can convert markdown documents into .docx files for Microsoft Word. These
files have a default looking style set: blue headings and Calibri fonts. Pandoc
lets you provide a reference docx file, and it will use the styles defined in
that document instead. This repository contains my reference docx file.


Some code to download this file from github.

```r
curl::curl_download(
  "https://github.com/tjmahr/refdocx/raw/master/ref.docx",
  "ref.docx")
```
