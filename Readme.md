# NodeJS (backend) Structure guideline
Apply the structure from article -> [Best practices for Express app structure](https://www.terlici.com/2014/08/25/best-practices-express-structure.html)

## In this repos the file consisted with:
1. **controllers**: Contains all logic files.
2. **libs**: Contain all library wrapper files.
3. **middlewares**: Contain all data-adapter/middleware lib files.
4. **models**: Contain all database-related files
5. **configs**: Contain all environment config files (This should be ignored by .gitignore file)
6. **public**: Contain all public files that can show to the public (image, text file, etc.)
7. **tests**: Contain all test files
8. **.gitignore**
9. **.prettierrc**: For format the source-code style.
10. **app.js** (Or index.js that up to negotiation)
11. **package.json**
12. **yarn.lock** (This is my mistake, if you use NPM as package manager, please remove this file)

## For every project don't forget:
- [x] Edit the '.gitignore' file to allow git ignores the node_modules/ directory.
- [x] When edit/refactor source-code please create the git branch before starting.

## Useful web-site resources
- [Checking the compatability of JS function](https://caniuse.com/)
- [Create the 3D infrastructure diagram](https://cloudcraft.co/)
- [The Ultimate Web Code Generator](https://webcode.tools/)
- [Git flow utility](https://danielkummer.github.io/git-flow-cheatsheet/)
