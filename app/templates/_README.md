# <%= component_name %>

## Description
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Laboriosam commodi esse quis ipsam a iusto aut ratione ex optio ut! Illum alias voluptatibus dolores, perferendis deserunt totam illo reiciendis voluptatem.

## Instalation
Clone this repository and run:
```
$ npm install
```

## Start working in development mode:
```
$ npm run dev
```
This command will build your `.sass`, `.jsx` and `.js` files and open a local development environment, with hot reloading. A browser window will be opened as well, showing the entry point of your documents folder for development purposes.

## To work in TDD mode:
```
$ npm run test:watch
```
## To run unit tests only once:
```
$ npm test
```
# How to publish an npm package with your component
## Login to Schibsted private npm repository
Ask your team leader for the login credentials in order to have access to the [@schibstedspain](https://www.npmjs.com/~schibstedspain) npm repository. Then, just type:
```
$ npm-login
````
To log in with the company's credentials. After that, make sure to **commit your changes** to Github before publishing, in order to execute the **linting** tasks and **unit tests**. This is very important, since no npm package should be published without commiting the changes to its Github repository before. After commiting, type:
```
$ git release 1.0.0 // replace '1.0.0' with the proper version number
```
This will produce a release tag in Github in order to keep track of the different versions. After releasing in Github, publish in the npm repository by:
```
$ npm publish .
```
And that's all! You should be able to install your component from another repository. For example, if your component is named `sui-button`, you can installing with:
```
$ npm install -g @schibstedspain/sui-button --save-dev
```

## Usage
Lorem ipsum dolor sit amet, consectetur adipisicing elit. Non perspiciatis, quod eum perferendis, facere enim hic. Quibusdam deleniti, distinctio. Molestias error quibusdam quo similique, laborum iste libero dolorum saepe et.