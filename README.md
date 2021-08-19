## stantargets and Target Markdown for Bayesian model validation pipelines

The `targets` R package enhances the reproducibility, scale, and maintainability of data science projects in computationally intense fields such as machine learning, Bayesian Statistics, and statistical genomics. Recent breakthroughs in the targets ecosystem make it easy to create ambitious, domain-specific, reproducible data analysis pipelines. Two highlights include `stantargets`, a new rOpenSci package that generates specialized workflows for Stan models while reducing the required volume of user-side R code, and Target Markdown, an R Markdown interface to transparently communicate the entire process of pipeline construction and prototyping. The example Target Markdown report at <https://wlandau.github.io/rmedicine2021-pipeline> (source:  <https://github.com/wlandau/rmedicine2021-pipeline>) demonstrates both capabilities in a simulation-based workflow to validate a Bayesian longitudinal linear model common in clinical trial data analysis.

## Resources

Resource | Link
---|---
Slides | <https://wlandau.github.io/bayes-lund-2021/>
Slide source | <https://github.com/wlandau/bayes-lund-2021>
Pipeline report | <https://wlandau.github.io/rmedicine2021-pipeline/>
Pipeline source | <https://github.com/wlandau/rmedicine2021-pipeline>
`targets` | <https://docs.ropensci.org/targets/>
Target Markdown | <https://books.ropensci.org/targets/markdown.html>
`stantargets` |  <https://docs.ropensci.org/stantargets/>
Stan | <https://mc-stan.org/>
`cmdstanr` | <https://mc-stan.org/cmdstanr/>
`posterior` | <https://mc-stan.org/posterior/>

## Thanks

* `stantargets`: Melina Vidoni served as editor and Krzysztof Sakrejda and Matt Warkentin served as reviewers during the rOpenSci software review process.
* Target Markdown: Christophe Dervieux and Yihui Xie provided crucial advice during initial development.
* Richard Payne and Karen Price reviewed this Bayesian model validation project.
