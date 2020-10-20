# Python Package

## Install tools

```
# install first time
curl -sSL https://raw.githubusercontent.com/sdispater/poetry/master/get-poetry.py | python
# update
poetry self:update
```

## Setup library

- run `package=???` in your console to set a name for your new python package
- then run the `poetry new...` command to create the package template

```
package=
poetry new python_package_$package --name=$package --src
```

## Link to GitHub repo

 - now it's time to link the new folder to your github repository
 - `REPO_NAME` is the name of the github repository

```
cd python_package_$package
git init
git remote add origin https://github.com/2018-Computational-Tools/REPO_NAME.git
git pull origin master
git add --all
git commit -m "Add initial project skeleton."
git push -u origin master
```

sdf
