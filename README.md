# Reproducible report: Network meta-analysis of fungicide effects on white mold epidemics and soybean yield

This repository contains all files needed to reproduce the analysis 


# Authors of the content

Emerson Del Ponte (delponte@ufv.br)  
Jhonatan Barro 

# Overview of contents

The root of the repository contains files that set the website structure (menus, etc.) and style  (`.yml`, `.css`), as well as the citation/reference style. There are four `.Rmd` files that generates each html, which are separated according to the convention of a research compendium.

- `index.Rmd`: Describe the research, objectives, authorship, etc.
- `data.Rmd`: Contains the raw or raw-derived data.
- `code.Rmd`: Produces the main analysis report with a template that follows the Wickham and Grolemund's [model for a data science project](http://r4ds.had.co.nz/introduction.html):  import -> tidy -> transform-visualize-model -> communicate 
- `manuscript.Rmd`: An example html manuscript template. It is intended to work as a pre-print version of the paper. 

There are three basic folders:

- `data/` - raw and further processed data.
- `Figures`/ - folder to place the figures generated in R
- `docs/` - html files of reproducible report with all text and figures.
- `preprint/` - A PDF version of the accepted manuscript


# Licenses

Manuscript: [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/)

Code: [MIT](https://opensource.org/licenses/MIT) year: 2017, copyright holder: Emerson Del Ponte

Data: [CC-0[(https://creativecommons.org/publicdomain/zero/1.0/)] attribution requested in reuse

# Contact

Emerson Del Ponte, Associate Professor, Departmento de Fitopatologia, Universidade Federal de Viçosa, Viçosa, MG Brazil
(+55) 31 38991103 
delponte@ufv.br
Twitter: @emdelponte

