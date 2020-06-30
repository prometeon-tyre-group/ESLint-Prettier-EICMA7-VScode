## ESLint PRETTIER setup for VS Code & EICMA7

### Instructions, Full Version:

1. Clone or download the Repo in the root folder of your App

2. Install Airbnb config and all the required dependencies:
   `npx install-peerdeps --dev eslint-config-airbnb`

3. Install Priettier and ESLint and their dependencies:
   `npm install -D eslint prettier eslint-config-prettier eslint-plugin-prettier`

4. Install VS Required extensions:
   `ESLint & Prettier`

#### Optional:

In VS Code settings set auto format on save:
`"editor.formatOnSave": true`

### Instructions, Light Set Up:

For a lighter version of the SetUp you can start only with the Priettier Configuration (Suggested at the Beginning):

1. Clone or download the Repo in the root folder of your App, erase the .eslintrc.json

2. Install Priettier and ESLint and their dependencies:
   `npm install -D prettier`

3. Install VS Required extensions:
   `Prettier`

### Notes:

ES Lint is set to use at least EICMA6 best pratices, no var allowed and a suggestion of not using let without good reason.

The Airbnb guidelines ensure to keep your code clean and tight. For more informations about guidelines and style vist the following url:
https://github.com/airbnb/javascript

Prettier is set to use single quotes, to prefer no brackets around single props and with a decent amount of tab width.

ADDENDUM: Things may be changed in the future to keep up with best practices, the file repo IS NOT in the final version!
