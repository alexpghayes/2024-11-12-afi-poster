---
output:
  pdf_document: default
  html_document: default
---
# TODO

- add title
- add abstract
- add png of poster to readme for convenience on github

## Converting from PDF to TIFF or PNG for printing on online display

```sh
magick -density 300 -quality 85 -format tiff poster.pdf AlexHayes-ACIC2023.tiff
magick -density 300 -quality 90 poster.pdf AlexHayes-ACIC2023.png
```