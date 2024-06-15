# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `yarn start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `yarn test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `yarn build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `yarn eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `yarn build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

## Additional Commands

### Modify terminal

(nano == open)

    sudo nano zshrc
    sudo nano bashrc

## Find /etc folder

    open /etc
    cd /etc

## Install

1.  brew
2.  nodejs (executing JS code)

    - Check the version

            node -v

    - also use to upgrade and to install all packages in package.json

            npm sudo npm install -g npm@latest

            sudo n stable

    - Check the version

            npm -v

3.  yarn

        sudo npm install add --global yarn
        sudo npm upgrade --global yarn

4.  git

        brew install git
        brew upgrade git

## Config Gitbhub

        git config --global user.name “<github username>”
        git config --global user.email <github email>

## GitHub CLI

        brew install gh
        brew upgrade gh

## Authenticate Github account

        gh auth login
        gh auth status

## Check repo list

        gh repo list

## Install bootstrap

        npm install bootstrap@5.3.3

## Install vue with new folder

        npm create vite@latest <Project Name> -- --template react

- no need to run this if the project already have vite

## Run app using npm

    npm run dev

## Create yarn react app and new repo in Github

1.  Go to target local root folder

    - also initializes git (git init)
    - yarn discourages using global packages

            yarn create react-app <project folder name>

2.  Go to created new folder

    - to install yarn

          yarn

    - to upgrade yarn version

          yarn upgrade

    - to run project

          yarn start

## Close Session Terminal

    Ctrl + C

## To open Code in Visual Studio

    code .

## Check the Remote Repository List

    gh repo list

## Create Remote Repository to an Existing Local Repository

Go to target local root folder

        gh repo create
        (Push an existing local repository to Github)

## Published existing local repo to Github

Go to target local root folder

    git status

    git add . (For all files)

    git commit -m “<commit message>”

    git status

    git remote -v

    git push -u origin master

### git init (in the target folder) - for app created in react, this is automatically initialized

## Other Git commands

    git clone <repo url>

    git checkout -b <new branch name>

    git push origin master - to get the latest code version

    git add .  (For all files)
    git add <name of file> (individual files)

    git commit -m “<commit message>”

    git status (to check modified files)

    git remote -v

## To confirm remote has been added

    git remote add origin https://github.com/jenniferdevega/<new repo name>.git

    git push -u origin master

## To update current local repo

    git pull origin master or main

    git remote update origin -- prune

    git branch -a

## To setup auto upstream(so not to use the git push -u origin master)

    git config --global push.autoSetupRemote true

    git push

## Yarn commands

    yarn test
    yarn build

## API Calls

Axois - common library for making API calls

    npm install axios
    yarn add axios

    curl -u "jenniferdevega_yV78hL:csphZQZzc7nzTKjfTjzk" \ -X GET "https://www.browserstack.com/user/ip_access_list"
