# heroku-buildpack-pandoc

A buildpack provides `pandoc` and `pandoc-citeproc`.

## install

```
heroku buildpacks:add https://github.com/Affygility/heroku-buildpack-pandoc.git
```

then you'll got buildpacks like this:

```
❯ heroku buildpacks
=== app Buildpack URLs
1. heroku/python
2. https://github.com/Affygility/heroku-buildpack-pandoc.git
```

## This fork

We set the pandoc version to `3.6.3`.