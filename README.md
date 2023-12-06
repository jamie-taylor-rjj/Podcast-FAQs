# Podcast-FAQs

A repo containing a number of FAQ documents for the different podcasts that RJJ Creates

The markdown file found within this directory is used to quickly generate a Guest FAQ for interviews. This document is then sent to all guests who have arranged to be on the show.

## Where to Start

If reading on GitHub, please start with the [guest-faq.md](./guest-faq.md) file. Or if you would rather, please see the [releases](https://github.com/jamie-taylor-rjj/Podcast-FAQs/releases) page to grab the latest automatic build of a single PDF.

## Auto-Render

This repository is set up with GitHub Actions, and will automatically render the contents of the PDF when a push is made to the Master branch. The latest version of the rendered document can be found in the [Actions tab](/actions).

### Auto Build Status

![main](https://github.com/jamie-taylor-rjj/Podcast-FAQs/workflows/main/badge.svg?branch=master)

## Licence Used

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

See the contents of the LICENSE file for details

## Code of Conduct

Podcast-FAQs has a Code of Conduct which all contributors, maintainers and forkers must adhere to. When contributing, maintaining, forking or in any other way changing the code presented in this repository, all users must agree to this Code of Conduct.

See [Code of Conduct.md](CODE_OF_CONDUCT.md) for details.

## Pull Requests

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

Pull requests are welcome, but please take a moment to read the [Code of Conduct](CODE_OF_CONDUCT.md) before submitting them or commenting on any work in this repo.

## Manually Rendering to PDF

One of the quickest and easiest ways to render this markdown to a PDF (for example) is to use [PanDoc](https://pandoc.org/), which is available for free. In order to render the Guest FAQ as a PDF, simply run the following command:

``` bash
pandoc about.md guest-faq.md ./show-specifics/dotnetcore.md ./show-specifics/wafflingtaylors.md --pdf-engine=xelatex -o guest-faq.pdf --toc
```

This render the guest-faq.pdf. However the resulting PDF has very wide margins, as is the default in TeX based systems (which is what pandoc uses in the conversion). To produce a version of the document with smaller margins, use the following command:

``` bash
pandoc about.md guest-faq.md ./show-specifics/dotnetcore.md ./show-specifics/wafflingtaylors.md --pdf-engine=xelatex -V geometry:"top=2cm, bottom=1.5cm, left=2cm, right=2cm" -o guest-faq.pdf --toc
```

## Page Breaks

As the input files in this repo are markdown and they will be processed by pandoc's LaTeX engine, we can make use of `\pagebreak` commands. These are LaTeX native _requests_ to the LaTeX engine to place the content which follows the request on the next page. This is different to `\newpage`, which acts more like a demand than a request - the result of `\pagebreak` isn't guaranteed to happen if there is already a natural page break following it.
