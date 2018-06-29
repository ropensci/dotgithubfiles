rOpenSci .github files
======================

These templates are part of our guidance for package authors. Cf [our gitbook](https://ropensci.github.io/dev_guide/) in particular the [chapter about collaboration](https://ropensci.github.io/dev_guide/collaboration.html).

Includes:

* [**CONTRIBUTING.md**](dotgithub/CONTRIBUTING.md)
* [**issue_template.md**](dotgithub/issue_template.md)
* [**pull_request_template.md**](dotgithub/pull_request_template.md)

How to use the templates:

**You can use the `rodev::use_ro_github()` function of [`rodev`](https://github.com/ropenscilabs/rodev) to perform all three steps at once**, or

* Put the content of [dotgithub folder](dotgithub/) i.e. these three files in a `.github` directory in the base of your R package.
* Update the `CONTRIBUTING.md` file with the package name.
* Make sure to add a line with `.github` in your `.Rbuildignore` file in your package as well. E.g. run `usethis::use_build_ignore(".github")`.

------

For more info on template files for GitHub repos:

* Setting guidelines for repository contributors: <https://help.github.com/articles/setting-guidelines-for-repository-contributors/>
* Issue and PR templates: <https://help.github.com/articles/about-issue-and-pull-request-templates/>

Note: These files are mostly not specific to rOpenSci - there are a few items in the files specific to rOpenSci, but can be easily removed.
