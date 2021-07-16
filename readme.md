# Mountebank example

## Prerequisites
Node version 8.10 or higher should be installed. In this example I am using node version 14

## Installation
```console
npm install 
```

## Structure

- `mountebanke-helper.js` this is the mountebank client which automatically sends post requests to the Mountebank instance
- `hello-server.js` this is our imposter or mock service. Each imposter contains a stub which that determine the response that the imposter will give
- `customer-service.js` this is another imposter with more logic in it. This service takes a parameter from the url and uses it to look up a record in a csv file

