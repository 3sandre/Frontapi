# Frontapi
# Title : React crud app for the statistics of the soccer players of the national team of Togo

This includes actions related to data collection, processing and retrieval under the node.js environment using express.js and react.js.



### . URL


   https://sandrineftf.netlify.app/


### - Method :

<The request type>

`GET` | `POST` | `DELETE` | `PUT`

### - URL Params :

#### Required:

`id=[integer]`

 ### `Tools used to build the React app :`

####  - NodeJS
####  - Reactjs
####  - Expressjs

 ####  - Express.js – Fast, unopinionated, minimalist web framework for [Node js](https://nodejs.org/en/)
 
 ### `Packages installed :`
 
#### - nvm – Node Version Manager
#### - npm – Node Package Manager
#### - Node.js
#### - Express installed with npm (npm install express body-parser morgan).

 ### `How to Use :`
 
 #### - POSThttps://sandrineftf.netlify.app/api/post
 
 - This will create a player

 `- this is the input examples
  {
    "id": 7,
    "name": "ama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`
 
`- and it will return json file like this
  {
    "id": 7,
    "name": "ama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`


#### - GET https://sandrineftf.netlify.app/api/get

 `- This will get the stats for player 7
 {
    "id": 7,
    "name": "ama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`
 #### - PUT https://sandrineftf.netlify.app/api/update
 
 . This will update the stats for player 7
 `- this the input 
 {
    "id": 7,
    "name": "amama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`
  
  
 - and it will return json file like this
`{
    "id": 7,
    "name": "amama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`
  
  #### - DELETE https://sandrineftf.netlify.app/api/remove
  . This will delete the stats for player 10
  
  ` - this the input 
 {
    "id": 10,
    "name": "amama",
    "lastname": "ama",
    "nickname": "amavi",
    "age": 45,
    "contacts": 456788900,
    "wins": 45,
    "losses": 45
    
  }`
