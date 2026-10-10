# Gene Expression Classifier · UI Demo

**A small R Shiny prototype for exploring a classifier interface.**

`R` · `Shiny` · `flexdashboard` · `Learning project`

## What it shows

Choose a number of genes and click **Build Classifier** to display a sample plot and score.

**Both outputs are random placeholders.** The repository contains no gene-expression dataset, trained classifier, or real PCA calculation. It demonstrates the interface, not a biological result.

## Open the demo

Install R and an editor that supports R Markdown, then install the packages:

```r
install.packages(c("shiny", "flexdashboard", "rmarkdown", "knitr"))
```

Open [shinyapp.io.Rmd](shinyapp.io.Rmd) and run its chunks, including the final `shinyApp(ui = ui, server = server)` call. The source credits the original notebook author as Yiping.
