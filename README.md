rOpenSci .github files
======================

These templates are part of our guidance for package authors. Cf [our gitbook](https://ropensci.github.io/dev_guide/) in particular the [chapter about collaboration](https://ropensci.github.io/dev_guide/collaboration.html).

Includes:

* [**CONTRIBUTING.md**](dotgithub/CONTRIBUTING.md)
* [**issue_template.md**](dotgithub/issue_template.md)
* [**pull_request_template.md**](dotgithub/pull_request_template.md)

Steps:

* Put the [dotgithub folder](dotgithub/) containing these three files in a `.github` directory in the base of your R package.
* Update the `CONTRIBUTING.md` file with the github owner (e.g., `ropensci`) and repo name (e.g., `foobar`).
* Make sure to add a line with `.github` in your `.Rbuildignore` file in your package as well. E.g. run `usethis::use_build_ignore(".github")`.

------

For more info on template files for github repos:

* Setting guidelines for repository contributors: <https://help.github.com/articles/setting-guidelines-for-repository-contributors/>
* Issue and PR templates: <https://help.github.com/articles/about-issue-and-pull-request-templates/>

Note: These files are mostly not specific to rOpenSci - there are a few items in the files specific to rOpenSci, but can be easily removed.
