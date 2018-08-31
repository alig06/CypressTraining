# CypressTraining
UI test trainings with Cypress
# Installation
>> **1.** `cd /your/project/path`

>> **2.** `npm install cypress --save-dev`

> Make sure that you have already run **[npm init](https://docs.npmjs.com/cli/init)** or have a node_modules folder or **"package.json"** file in the root of your project to ensure cypress is installed in the correct directory.

## Opening Cypress
> If you used npm to install, Cypress has now been installed to your **./node_modules directory**, with its binary executable accessible from **./node_modules/.bin**. This means you can call it from your project root either of the following ways:

>> **3.** `./node_modules/.bin/cypress open`

## Adding Npm Scripts
> While there’s nothing wrong with writing out the full path to the Cypress executable each time, it’s much easier and clearer to add Cypress commands to the scripts field in your **package.json** file.


>>**4.**
**`{
  // package.json
  "scripts": {
    "cypress:open": "cypress open"
  }
}`**
***
## Run us Tests
**5.**_(edited)_ 
> We will starting to cypress with the following commands.
> This commands write in where the **'package.json'** folders. _For example(**YourProject/**)_ 

>> **`npm start`**

>> **`npm run cypress:open`**

### >>>> _Cypress is ready for use._


* Let’s create a new file in the cypress/integration folder that was created for us:

>> **`touch {your_project}/cypress/integration/sample_spec.js`**
* **Our tests in this directory**: {your_project}/cypress/integration/


***

>>> **If you want to detailed explanation visit a url [Cypress.io](https://docs.cypress.io/guides/getting-started/installing-cypress.html)**
***
