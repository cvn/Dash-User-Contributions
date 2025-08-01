# Documentation

## Scikit-Learn Authors

- Aziz Alto (https://github.com/iamaziz)
- Angelo Varlotta (https://github.com/capac)
- Christian Stade-Schuldt (https://github.com/tafkas)
- Josh Devlin (https://github.com/jaypeedevlin)
- Joel Nothman (https://github.com/jnothman)
- Tianshu Wang (https://github.com/tshu-w)
- Xavier Yang (https://github.com/ivaquero)

## Instructions

### Method 1

- Requirements: Python 3.5+ on path; `optipng`
- Run: `./build.sh`

### Method 2

- download https://scikit-learn.org/stable/_downloads/scikit-learn-docs.zip
- remove `_download`, `_sources`, `binder`, `lite` and `notebooks` in`scikit-learn-docs`
- run the following command

```cmd
doc2dash -n scikit-learn -I preface.html scikit-learn-docs -v
tar --exclude='.DS_Store' -cvzf scikit-learn.tgz scikit-learn.docset
```
