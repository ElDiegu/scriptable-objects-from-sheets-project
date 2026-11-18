# scriptable-objects-from-sheets (development project)

This is the Unity project used to develop and test the **Scriptable Objects From Sheets** package.

The package itself lives in its own repository, included here as a git submodule at
`Packages/com.eldieguuu.scriptableobjectsfromsheets`:

<https://github.com/ElDiegu/scriptable-objects-from-sheets>

To install the package in your own project, see the installation instructions in that repository.

## Working on this project

Clone with submodules so the package is checked out:

```
git clone --recurse-submodules git@github.com:ElDiegu/scriptable-objects-from-sheets-project.git
```

If you already cloned without them, run `git submodule update --init`.

Package changes are committed and pushed from inside the submodule folder (to the package repository).
Afterwards, commit the updated submodule pointer in this project.
