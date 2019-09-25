## Features


This boilerplate includes the latest powerfull tools.

* **Next.js** - Minimalistic framework for server-rendered React applications.
* **Typescript** - Superset of JavaScript which primarily provides optional static typing, classes and interfaces.
* **Redux** - State management
* **Express.js**- Handles server-side rendering and integrated with Express.js
* **Built-in Project CLI**- Create pages, components, actions, reducers with one command by using built-in cli.
* **Sass/Scss** - CSS preprocessor, which adds special features such as variables, nested rules and mixins (sometimes referred to as syntactic sugar) into regular CSS.
* **Docker** - A tool designed to make it easier to create, deploy, and run applications by using containers.
* **Babel** -  The compiler for next generation JavaScript.
* **Eslint** - The pluggable linting utility.
* **Reverse Proxy** - A reverse proxy server is a type of proxy server that typically sits behind the firewall in a private network and directs client requests to the appropriate backend server
* **Bundler Analyzer** - Visualize size of webpack output files with an interactive zoomable treemap.
* **dotenv .config** - Expose environment variables to the runtime config of Next.js
* **Jest** - Javascript testing framework , created by developers who created react
* **Enzyme** - JavaScript testing utility for React that makes it easier to test your React Components output.
* **i18next** - An internationalization-framework which provides a function that takes a key, some options, and returns the value for the current language. Helps you to add language translation support to your app.

<br />

## Setup


1: Clone the repo

```sh
git clone 
```

2: npm or yarn or cnpm

```sh
npm install or yarn or cnpm install
```

3: Start the development server

```sh
npm run dev
```

<br />


## Deployment


### build

```sh
npm run build
```
```sh
npm run start
```


### Docker

create a docker image from Dockerfile
```sh
docker build .
```
start a container from image
```sh
docker run -p 3000:3000 <image_id>
```