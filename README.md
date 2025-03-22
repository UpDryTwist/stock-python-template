# stock-python-template
Stock run-of-the-mill Python template

# Getting started

See [copier documentation](https://copier.readthedocs.io/en/stable/) for more information.

Generally, will need to:
* ```pipx install copier```

# Creating a new project

Run with:
```bash
copier copy --trust https://github.com/UpDryTwist/stock-python-template.git my-project-directory
```

# Adding to an existing project

* Recommend renaming out the files that copier will be adding, and then editing back in the changes you want.
* Or just run it as normal and resolve the conflicts.

# Updating a project

Run with:
```bash
copier update --defaults
```
* Remoive `--defaults` to be prompted for each change.
* Add `--vcs-ref=HEAD` to update to the latest version of the template.
* Add `--confict inline` to put conflict markers inline