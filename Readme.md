# NodeJS (backend) Structure guideline
Apply the structure from https://www.terlici.com/2014/08/25/best-practices-express-structure.html

## In this repos the file consisted with:
1. controllers: Contains all logic files.
2. libs: Contain all library wrapper files.
3. middlewares: Contain all data-adapter/middleware lib files.
4. models: Contain all database-related files
5. tests: Contain all test files
6. .gitignore
7. .prettierrc: For format the source-code style.
8. app.js (Or index.js that up to negotiation)
9. package.json
10. yarn.lock (This is my mistake, if you use NPM as package manager, please remove this file)

## For every project don't forget:
### 1. Edit the '.gitignore' file to allow git ignores the node_modules/ directory.
### 2. When edit/refactor source-code please create the git branch before starting.
