# 📟 Password Generator
Password generator and strength validator.

You can generate passwords between 6 and 16 characters, including uppercase, lowercase and numbers, and validate the strength of a given password, relying on the zxcvbn library. It offers suggestions with 5 levels of validation.

## 📑 Summary

- [Password Generator](#-password-generator)
  - [Summary](#-summary)
  - [Built With](#-built-with)
    - [About The Technologies Used](#-about-the-technologies-used)
  - [Run The Project Locally](#--run-the-project-locally)
  - [Run The Project With Docker](#-run-the-project-with-docker)
  - [Run The Tests](#-run-the-tests)
    - [Using The Password Generator](#-using-the-password-generator)
  - [Versioning](#-versioning)
  - [Author](#-author)
  - [Copyright and license](#%EF%B8%8F-copyright-and-license)

## 🔨 Built With
    
| Tecnology | Description |
| ------ | ------ |
| [Node.js v14.15.5](https://nodejs.org/en/) | JavaScript runtime built on Chrome's V8 JavaScript engine. |
| [React.js v17.0.2](https://reactjs.org/) | A JavaScript library for building user interfaces. |
| [Typescript  v4.2.3](https://reactjs.org/) | JavaScript with syntax for types.. |
| [@babel/preset-react v7.13.13](https://react-redux.js.org/) | Babel is a toolchain that is mainly used to convert ECMAScript 2015+ code into a backwards compatible version of JavaScript in current and older browsers or environments. |
| [@babel/preset-typescript v7.13.0](https://babeljs.io/docs/en/babel-preset-typescript/) | This preset is recommended if you use TypeScript, a typed superset of JavaScript.. |
| [JEST v26.0.22](https://jestjs.io/) | Jest is a delightful JavaScript Testing Framework with a focus on simplicity. |
| [Cypress  v6.8.0](https://www.cypress.io/)  | Fast, easy and reliable testing for anything that runs in a browser. |
| [Font Awesome v5.15.3](https://fontawesome.com/) | The web's most popular icon set and toolkit. |
| [react-copy-to-clipboard v5.0.3](https://www.npmjs.com/package/react-copy-to-clipboard/) | Copy to clipboard React component. |
| [zxcvbn password strength v4.4.2](https://github.com/dropbox/zxcvbn/) | A password strength estimator inspired by password crackers. |
| [Docker Desktop on Windows v4.4.2](https://docs.docker.com/docker-for-windows/install/) | Accelerate how you build, share, and run modern applications. |

### 🙋 About The Technologies Used
This project includes both JEST and Cypress for testing the code and the interface. The project is built on top of Docker, which makes it easily portable.

## 🚀 Run The Project Locally
To start with, you can clone this repo pasting the following command in a shell:
```sh
git clone https://github.com/Ch3ssMaster/password-generator.git
```
To continue, I recommend you to `maintain the original file package-lock.json` and install the node packages with the following command:
```sh
npm ci
```
Once the installation has finished, you can launch the app with the following command: 
```sh
npm start
```
The password generator will run in the URL: [http://localhost:3000/](http://localhost:3000).

## 🐳 Run The Project With Docker
The easiest way to run this project. Download the container from Hub (assuming you have docker up and running) with the following command:
```sh
docker pull ch3ssmaster/agile
```
Then, you can launch the container and open it in the browser ([http://localhost:3000/](http://localhost:3000)):
```sh
docker run -d -p 3000:3000 ch3ssmaster/agile
```
📣	** You must to use port 3000 in order to be able of executing Cypress tests.**

## 🧪 Run The Tests
For launching the JEST test run the following command:
```sh
npm run j-w
```
To execute Cypress tests in navigator mode run: 
```sh
npm run c-open
```
While running in navigator mode, you will need to confirm the copy-to-clipboard action by pressing the `"Accept"` button, in the pop-up window.
You can also run Cypress in shell mode:
```sh
npm run c-run
```

### 💡 Using The Password Generator
In the `"Home"` section, you can set up the security parameters for your password, choosing to include uppercase, lowercase and numbers (by default, only lowers). In addition, you can choose a password length between 6 and 16 characters (12 by default). Press `"Generate Password"` to generate a new one.

The `"Hit to copy"` button will copy your password to the clipboard, and now you can move to the `"Password Checker"` section to verify the strength of your generated password. Of course, you can test whatever password that you desire. The validator will give you sympathetic feedback.

## ⌚ Versioning
`v1.0.0-alpha`
The site use [SemVer](http://semver.org/) for versioning. 

## 🔗 Author
**Antonio Cebrián Mesa** - _Full Stack Web Developer & Informatics Teacher_ -
- [My personal Website](http://clasesinformaticagranada.es/)
- [My Tetris Game Version](http://clasesinformaticagranada.es/tetris)
- [Follow me on Twitter](https://twitter.com/hacking_the_web)
- [For projects and classes](https://www.linkedin.com/in/antonio-cebri%C3%A1n-mesa)

## ©️ Copyright And License

Code and documentation copyright 2021 the [Author](https://www.linkedin.com/in/antonio-cebri%C3%A1n-mesa). Code released under the [MIT License](https://github.com/Ch3ssMaster/password-generator/blob/main/LICENSE.md). 