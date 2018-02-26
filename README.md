# npm-scripts-conventional-changelog
Configuration for [npm-scripts-config](https://www.npmjs.com/package/npm-scripts-config) where [conventional-changelog](https://www.npmjs.com/package/conventional-changelog), [commitlint](https://www.npmjs.com/package/commitlint) and [commitizen](https://www.npmjs.com/package/commitizen) are ready to use.

This configuration expose three commands:

- **commit**: trigger [commitizen](https://www.npmjs.com/package/commitizen) to guide the developer to write a standardized commit message
- **commitmsg**: used by [husky](https://www.npmjs.com/package/husky) to lint commit message when git commit is run
- **version**: generates a changelog and it to the commit

[commitizen](https://www.npmjs.com/package/commitizen), [commitlint](https://www.npmjs.com/package/commitlint) and [conventional-changelog](https://www.npmjs.com/package/conventional-changelog) are configured to follow [angular conventions](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#commit).