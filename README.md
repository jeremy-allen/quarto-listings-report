# quarto-listings-report

[See the report!](https://jeremydata.quarto.pub/lovelace-weekly-ops-report/)

## Why use cards in a report?

- Often tables of data are too wide to easily read in a quick meeting
- Some long text fields in tables are cumbersome
- Cards can more neatly arrange the same data
- Cards can be easier to read quickly

## What is different here?

Using a modified quarto listings page as a report instead of a blog landing page. In the `custom.scss` file I added a scroll bar to the card description field to allow for longer text in the field. In the `opps_weekly_cards.qmd` I set a new max description length in the YAML of each listings definition.

## Can I use this?
Yes. However, in this demo project the content for the cards is coming from handmade files `opps1.yml` and `opps2.yml`. In a real-world project, chances are my data will be in a data frame or tibble. I would then use the [yaml](https://github.com/vubiostat/r-yaml) package to convert the data frame to yaml for me.

## Help

- [Quarto guide to listing pages](https://quarto.org/docs/websites/website-listings.html)
- [Quarto guide to custom listings](https://quarto.org/docs/websites/website-listings-custom.html)
- [Quarto guide to HMTL theming](https://quarto.org/docs/output-formats/html-themes.html)
