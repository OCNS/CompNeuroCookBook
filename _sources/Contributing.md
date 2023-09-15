(contributing)=
# Contributing new snippets

Please follow this process to contribute new snippets to the cook book:

- [fork this repository](https://github.com/OCNS/CompNeuroCookBook)
- add a new file with your snippet using the provided template below
- add your snippet file into the `source/_toc.yaml` file (the table of contents)
- open a pull request

Your pull request will be reviewed and merged by a fellow contributor.

## Template

Please use this template to submit new entries to the cook book, replacing the code block with your snippet.
Please see the [Jupyterbook documentation](https://jupyterbook.org/en/stable/reference/cheatsheet.html#code) for more information on including code.
The first line is a reference that allows your snippet to be referenced from other pages in the Jupyterbook.

````markdown

(language:snippet-slug)=
# Snippet title

A short description of the snippet, noting why its useful.

A list of requirements/setup steps (for example, for Python snippets, one may need to install some packages)

- step 1
- step 2

Reference list

- reference link 1
- reference link 2

```bash
# some code
```

````
