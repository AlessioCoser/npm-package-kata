[![Build Status](https://travis-ci.org/AlessioCoser/npm-package-kata.svg?branch=master)](https://travis-ci.org/AlessioCoser/npm-package-kata)

# npm-package-kata

# requirements

- npm account (npm package)
- github (repo & CI)

# create the npm package

- create your project folder.
- initialize git repository with `git init` and create github repository
- initialize the npm project with `npm init --yes`.
- add `.travis.yml` and push to github.
- link [travis](https://travis-ci.org) with github via web.
- `git push` and see the CI running.
- copy the badge from the project CI page and add it to README.
- `npm publish` the module and make it available on npm.

# publish a new version

make some changes, and bump version with

```
npm version patch
# or
npm version minor
# or
npm version major
```

and `git push && npm publish`

Thanks to [Christian Fei](https://github.com/christian-fei)
