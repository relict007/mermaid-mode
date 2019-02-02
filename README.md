# mermaid-mode
Emacs major mode for working with [mermaid graphs](https://mermaidjs.github.io/)

![alt text](screenshot.jpg "Screenshot")

## Installation
Load the `mermaid-mode.el` file, and install `mmdc` binary from the [mermaid.cli project](https://github.com/mermaidjs/mermaid.cli) if you plan to compile graphs in Emacs.

## Usage
Currently supporting flow charts and sequence diagrams with syntax coloring and indentation.

```
C-c C-c to compile to an image
C-c C-o to open in the live editor
C-c C-d to open the official doc
```

## Customization
You can specify the location of `mmdc` with the variable `mermaid-mmdc-location`, the default assumes you have the binary in your exec PATH.

By default `mmdc` will compile to png format. You can change that by setting the variable `mermaid-output-format`.

## Bugs & Issues
- fix indentation for `else` statement
