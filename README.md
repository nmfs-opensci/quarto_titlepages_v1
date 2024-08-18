# quarto_titlepages_v1 <a href="https://github.com/nmfs-opensci/quarto_titlepages_v1"><img src="https://raw.githubusercontent.com/nmfs-opensci/assets/main/images/GitHub-Mark-32px.png" align="right"/></a>

[Documentation](https://nmfs-opensci.github.io/quarto_titlepages_v1/)

tldr; Open the `titlepages` folder, then open the `bg-image` folder, then open `article.qmd`. Scroll to the pdf format section of the yaml. Then open `before-body.tex`. That is what is giving you control of the frontmatter. Read the [How to use](https://nmfs-opensci.github.io/quarto_titlepages_v1/03-how-to-use.html) section of the documentation to get an overview.

This template makes a custom title page using the information in the YAML (from the `xyz.qmd` for an single doc and from `index.qmd` for a [Quarto](https://quarto.org/) book). Note, this is not the quarto_titlepages extension. This repo is for LaTeX users who want to DYI a titlepage with their own Pandoc template partials. The Quarto extension lives here: [quarto_titlepages](https://github.com/nmfs-opensci/quarto_titlepages).

<a href="https://nmfs-opensci.github.io/quarto_titlepages/images/paste-CC55A28D.png"><img src="./images/bg-image.png" width="200"/></a>

------
This work is uses [Quarto](https://quarto.org/) ([citation](https://github.com/quarto-dev/quarto-cli/blob/main/CITATION.cff)). The default document classes for Quarto are the KOMA-script scrbook and scrartcl document classes. This repo also includes a copy of the Springer [svmono](https://www.springernature.com/gp/authors/campaigns/latex-author-support) document class, CRC/Chapman & Hall krantz document class, and the Elsevier elsarticle document class.
