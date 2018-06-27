rOpenSci .github files
======================

These files are mostly not specific to rOpenSci - there are a few items in the files specific to rOpenSci, but can be easily removed.

Includes:

* **CONTRIBUTING.md**
* **issue_template.md** (see the [raw text](https://raw.githubusercontent.com/ropensci/dotgithubfiles/master/issue_template.md))
* **pull_request_template.md** (see the [raw text](https://raw.githubusercontent.com/ropensci/dotgithubfiles/master/pull_request_template.md))

Steps:

* Put these three files in a `.github` directory in the base of your R package.
* Update the `CONTRIBUTING.md` file with the github owner (e.g., `ropensci`) and repo name (e.g., `foobar`).
* Make sure to add a line with `.github` in your `.Rbuildignore` file in your package as well.

------

For more info on template files for github repos:

* Setting guidelines for repository contributors: <https://help.github.com/articles/setting-guidelines-for-repository-contributors/>
* Issue and PR templates: <https://help.github.com/articles/about-issue-and-pull-request-templates/>
