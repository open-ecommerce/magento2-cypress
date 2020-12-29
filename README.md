![Magento2, End to End testing, Functional Testing ](m2-cypress-open-ecommerce.png)

# Magento 2 Functional Testing

## Frontend tests on Magento 2 with Cypress

### Introduction
The tests located in the cypress/integration directory work with Magento2 luma template.

### Prerequisites

#### Install [Node.js][node]

    sudo apt install nodejs

#### Install [Cypress][cypress]
    
    npm install cypress    
   
(if dosn't work add the --save-dev to recreate the json)

*If you are runing the tests in Win 10 remember to add the node System variable at Environment Variables: NODE_HOME path to node.js*

### Howto run the tests
Run all the tests with the command below:

    ./node_modules/.bin/cypress open


### Troubleshooting


[node]: https://nodejs.org/en/download/
[cypress]: https://docs.cypress.io/guides/overview/why-cypress.html#In-a-nutshell
