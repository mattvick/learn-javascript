# Learn JavaScript

## Day 0 - Learn the basics directly in the browser console

1. Open Google Chrome
1. Open any webpage
1. Press <kbd>Command</kbd> + <kbd>Option</kbd> + <kbd>J</kbd> (Mac) to Open the the Chrome DevTools console - [Other ways to open Chrome DevTools](https://developers.google.com/web/tools/chrome-devtools#open)
1. Constants, strings and semicolons `const greeting = 'Hello';`
1. Variables and numbers `var amount = 4;`
1. Work through the [Language basics crash course](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/JavaScript_basics#language_basics_crash_course)

## Day 1 - Project and account setup

### Topics

* Where to find help
* Terminal and commands - [iTerm2](https://iterm2.com/)
* macOS package management - [Homebrew](https://brew.sh/)
* JavaScript runtime - [Node.js](https://nodejs.org/en/)
* JavaScript package management - [Node Pagage Manager (NPM)](https://www.npmjs.com/), [Yarn](https://yarnpkg.com/)
* Code editor - [Visual Studio Code](https://code.visualstudio.com/)
* Linting - [ESLint](https://eslint.org/)
* Rapid prototyping playground - [Quokka.js](https://quokkajs.com/)

### JavaScript Documentation

MDN Web Docs (previously Mozilla Developer Network):

* [Reference](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference)
* [Tutorials](https://developer.mozilla.org/en-US/docs/Web/JavaScript#tutorials) - these appear to be focused on building web pages

### Computer setup tasks

Download and install the following applications:

1. [Visual Studio Code](https://code.visualstudio.com/)
1. [iTerm2](https://iterm2.com/)
1. [Homebrew](https://brew.sh/)

### Project setup tasks

1. Open iTerm
1. Create a directory `mkdir learn-javascript`- _choose your own directory name_
1. Change to the created directory `cd learn-javascript` - _use the directory name you chose_
1. Create a Visual Studio Code workspace

### JavaScript setup tasks

1. Brew install Yarn `brew install yarn` - _if needed brew install Node.js `brew install node`_
1. Create a `package.json` file `yarn init`
1. Add a Git ignore file `echo "/node_modules" >> .gitignore`
1. Create an `index.js` file `touch index.js`

### ESLint setup tasks

1. Install [ESLint Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
1. Create an ESLint config file `npx eslint --init`
1. Set the [no console](https://eslint.org/docs/rules/no-console) rule to `off` in the ESLint config `'no-console': 'off',`

### Quokka.js setup tasks

1. Install [Quokka.js Visual Studio Code extension](https://marketplace.visualstudio.com/items?itemName=WallabyJs.quokka-vscode)

## Day 2 - Coding

1. Objects and properties (literal notation) `const data = {};` - [read more](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)

To do more...

## Day 3 - Git setup and pushing changes

Typically when setting up a new project this would be the first step. To gently indroduce you to new concepts I've waited until day 3 to introduce this.

### Topics

* Version control and source repositories - [Git](https://git-scm.com/)
* Code sharing, issue tracking - [GitHub](https://github.com/), [GitLab](https://about.gitlab.com/), [BitBucket](https://bitbucket.org/)

### Account and authentication setup tasks

1. Create a [GitLab](https://about.gitlab.com/) account
1. [Generate an SSH key pair](https://docs.gitlab.com/ee/ssh/#generate-an-ssh-key-pair)
1. [Add the public SSH key to your GitLab account](https://docs.gitlab.com/ee/ssh/#add-an-ssh-key-to-your-gitlab-account)
1. [Verify that you can connect](https://docs.gitlab.com/ee/ssh/#verify-that-you-can-connect)

### Computer setup tasks

1. Download and install [GitHub Desktop](https://desktop.github.com/)

### Repository setup tasks

1. Initialise a local Git repository `git init` - _if needed install Git_
1. Create a remote Git repository on [GitLab](https://about.gitlab.com/)
1. Add the remote repository to our project `git remote add origin git@gitlab.com:mattvick/learn-javascript.git`
1. Add a read me file `echo "# Learn JavaScript" >> README.md`
1. Add all changes in the working directory to Git's staging area `git add .`

### Commit and push changes

1. Commit changes to Git with a message `git commit -m "Initial commit"`
1. Push changes to GitLab `git push -u origin master`

### Using GitHub Desktop

1. Viewing file diffs (changes) 
1. Commit and push changes
1. Pulling changes

## Day 4 - Git branches and merging

1. Fetching vs pulling
1. Merging via merge requests

To do more..

## Day 5 - Asynchronous JavaScript

1. [Read more](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Asynchronous)

To do more..

## Day 6 - ES6

To do more..

## Day 7 - TypeScript

To do more..

## Day 8 - React

To do more..
