# Mathematics Document LaTeX Template

This repository contains a template LaTeX document, intended for mathematics notes, reports and articles.

![Sample document](https://github.com/toddlj/math-doc-template/blob/master/examples/mathematics-report.png Sample document)

*Sample document from [project on Atiyah-Singer Index Theorem](https://www.toddljones.me/assets/files/atiyah-singer-index.pdf)*

## Features

It contains:

* [x] General document defaults from [latex-default-document](https://github.com/toddlj/latex-default-document):
    * [x] Character encoding information
    * [x] [FontAwesome](https://fontawesome.com/) icons
    * [x] Hyphenation for english
    * [x] French spacing
    * [x] Paragraphs indicated with new line and not indents
    * [x] Title, author and date exported as pdf metadata
    * [x] External links indicated by icon, and not coloured square
    * [x] Header with horizontal bar and section names
    * [x] Tables with `booktabs`
    * [x] Lists with `enumitem`
    * [x] Quotes with `csquotes`
    * [x] `tikz` and `graphicx` for diagrams and figures
    * [x] Standard math packages
    * [x] Math environments for Theorem, Lemma, etc.
* [x] Environments such as Theorem, Lemma, Proposition
* [x] Commands for mathematical objects from [latex-math-commands](https://github.com/toddlj/latex-math-commands):
    * [x] Standard number fields
    * [x] Linear algebra
    * [ ] Integration
* [x] Copyright and license information
* [ ] Build with Makefile.

## Installation

Perform the following commands to set up the template.

```shell
git clone https://github.com/toddlj/math-doc-template.git <document-name>
git submodule update --init
git remote remove origin
```

> Ensure you update the auther information, and that you change the license if you don't want to distribute your document under [CC-BY 4.0](https://creativecommons.org/licenses/by/4.0/).

## Repository information

### Maintainer

This repository is maintained by [Todd Liebenschutz-Jones](https://www.toddljones.me) ([email](mailto:dev@toddljones.me)).

### License

This repository is licensed by a [MIT License](https://opensource.org/licenses/MIT).
See [LICENSE.txt](https://github.com/toddlj/math-doc-template/blob/master/LICENSE.txt) for full terms.
