# Podcast-FAQs

A repo containing a number of FAQ documents for the different podcasts that RJJ Creates

The markdown file found within this directory is used to quickly generate a Guest FAQ for interviews. This document is then sent to all guests who have arranged to be on the show.

## Rendering to PDF

One of the quickest and easiest ways to render this markdown to a PDF (for example) is to use [PanDoc](https://pandoc.org/), which is available for free. In order to render the Guest FAQ as a PDF, simply run the following command:

``` bash
pandoc guest-faq.md .\show-specifics\dotnetcore.md .\show-specifics\wafflingtaylors.md --pdf-engine=xelatex -o guest-faq.pdf
```

This will produce a file similar to the [PDF found in this directory](./guest-faq.pdf). However the resulting PDF has very wide margins, as is the default in TeX based systems (which is what pandoc uses in the conversion). To produce a version of the document with smaller margins, use the following command:

``` bash
pandoc guest-faq.md .\show-specifics\dotnetcore.md .\show-specifics\wafflingtaylors.md --pdf-engine=xelatex -V geometry:"top=2cm, bottom=1.5cm, left=2cm, right=2cm" -o guest-faq.pdf
```
