# Diagram generator Test project for quarto

This "minimal working example" uses PlantUML and GraphViz via [Pandoc's official diagram-generator filter](https://github.com/pandoc/lua-filters/tree/master/diagram-generator#prerequisites) so you must install them and configure your system's environment variables according to the [filter's documentation]. Note that the filter is included in this repo for simplicity.

Quarto commands of interest:

To generate a PDF version (note the `pdf-engine: latexmk` setting in _quarto.yml):

```
quarto render diagram-test.qmd --to pdf
```

To generate the HTML version (note the `self-contained: true` setting in _quarto.yml):

```
quarto render diagram-test.qmd --to html
```

