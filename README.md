# use-gpr-npm-package-example
A simple example of how to use a npm package in the GitHub Package Registry

Uses [@codertocat/hello-world-npm](https://github.com/Codertocat/hello-world-npm/packages/10696). `.npmrc` has already been configured according to https://help.github.com/en/github/managing-packages-with-github-package-registry/configuring-npm-for-use-with-github-package-registry#installing-packages-from-other-organizations

## Steps

1. Create a Personal Access Token (PAT) with `repo` and `read:packages` scopes
2. Run `npm login --registry=https://npm.pkg.github.com`, use the token created in step 1 as your password.
3. Run `npm install`
4. Optional: run `npm update @codertocat/hello-world-npm`
5. Run `node index.js`
6. Celebrate - you just made use of a GitHub Package Registry package! 🎉