# rmarkdown-rtl-css
A simple CSS that I use for RMarkdown to compile html files rtl.

## Motivation
I use Rmarkdown to compile lessons with embedded R script and results.
I wanted the rendering to differentiate between code/results and markdown, rendering the latter rtl and the former ltr.
If your looking for a full fledged CSS to handle your `rtl` needs... keep looking - but it gets the job done.

## Usage
After downloading the CSS, simply refer to the files location in the yaml section of your Rmd script
like so:
`output: 
  html_document: 
    css: rmarkdown-rt-css.css
`
For further information on customizing Rmd files output, check out the RStudio website....

## Improvement

The basic idea is that everything should be `rtl` and every element or class we want `ltr` we should reference directly.
Im sure there is room for improvement, mostly to code chunk output.
I haven't gotten around to dealing with graphs yet, (though I'll probably get to it soon).

Feel free to contribute!!

