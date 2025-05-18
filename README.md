# SC Johnson "This We Believe" Text Analysis
This project analyzes SC Johnson's ["This We Believe"](https://www.scjohnson.com/en/about-us/this-we-believe) page using text mining techniques in R.

## What it does
- Extracts and cleans HTML paragraph text from the SC Johnson website
- Creates a term-document matrix
- Performs clustering to visualize thematic groupings
- Generates word clouds with sentiment-aware and color-customized styling

## Output
You can view the full results in the knitted HTML file: `scj_text_analysis.html` (generated from `scj_text_analysis.Rmd`).

## Tools used
- R
- R Markdown
- `tm`, `XML`, `lsa`, `cluster`, `wordcloud`, and `RColorBrewer` packages
