# GraphQL Notes

* go into the api folder in your terminal
* npm install when you're in there within your terminal
* create a .env file within this folder or do it locally
* then do = paste your api key here
* npm run dev opens a live server
* then go to localhost:5000/graphql

## Getting started with GraphQL

* The folder structure is all set up.
* You make all your requests in the schemas folder
* if you want to do any request first you must first go into the typedefs.
* if you want to do a get request you are going to put your request in the type query object
* if you are doing any kind of post request then you must put it into the type mutations object
* If it is a request that takes in a parameter put () next to it with a colon and the following return type
* if confused check out other requests
* then you go into the resolver and add in a request into the correct query or mutations section. Don't forget about the commas before and after adding the new function
* Then add your usual functionality into that new function you've made and it must recieve and return the information you gave it in the typedefs

## using GraphQL playground

* when in the playground :localhost:5000/graphql click query your server
* click the plus symbol next to your request and it will generate your request for you in the operation
* then click the request in the documentation tab and click the pluses for what you want to add to your request for testing.

## GraphQL help

* the graphql response will not tell you much so I would rely on your terminal. Add console logs and start looking from the beginning of your request and follow it along it's path until you fail to see the console.logs
