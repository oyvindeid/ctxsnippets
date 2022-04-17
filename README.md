# CTXSnippets

A collection of almost 200 [YASnippet](https://github.com/joaotavora/yasnippet) templates
for writing [ConTeXt](https://wiki.contextgarden.net/Main_Page) code in [Emacs](https://www.gnu.org/software/emacs).

## Installation

To install the snippets, clone this repo as

    $ git clone https://github.com/oyvindeid/ctxsnippets

and copy the `context-mode` directory to `yas-snippet-dirs`. 

Then run

    M-x yas-recompile-all RET
    M-x yas-reload-all RET

inside Emacs.

## Config variables

Three Emacs config variables can be set like

```lisp
(setq user-default-figures-dir "~/Pictures")
(setq user-default-bibtex-file "~/Documents/references.bib")
(setq user-default-csv-files-dir "~/csvfiles")  ;; PGF plot data source directory
```

in order to take full advantage of the installed templates.

## License

The software is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).

