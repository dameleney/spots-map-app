# SpotMap
Basic application for adding markers along with some metadata to a mongo db. Original purpose is to crowd source information about kiteboarding and windsurfing launches/spots around the globe. However, the general application could be used for adding any group of objects that include geo location specific data to a database.  
Uses MEAN (Mongo, Express, Angular, and Node)  
APIs Used: Google Maps

## Instructions to run locally
1) Install node modules  
`npm install`
2) Launch mongod in one terminal then run server.js  
`mongod`  
`node server.js`  
3) Open browser `http://localhost:3000/`

## ToDo
- Hide API keys from github
- Add field for spotskilllevel
- Fix up google map interface to allow drag and drop
- Deploy on... Heroku maybe using mLab MongoDB add-in https://elements.heroku.com/addons/mongolab
- Figure out domain name etc...
  - Domain name
  - Logging 
  - Addwords
  - SEO: register with google, make sure site is indexed properly, indexing of mongo db, research other techniques and best practices for SEO
- Add recapthca to add spot form to confirm user is not a robot https://developers.google.com/recaptcha/intro
- Add layer of user verification using http://openid.net/what-is-openid/ possibly
- Add OAuth https://elements.heroku.com/addons/auth0
- Add results pane that is a list of spots in search results and have clicking on result on map scroll and highlight result in list
- Add view for viewing spot summary
- Add marker clusters https://developers.google.com/maps/documentation/javascript/marker-clustering

## Reach goals
- Make robust site that users can rate location, suggest edits, and log sessions.
- Add concept of kiteboarding/windsurfing shop location
- Make similar concept for backcountry skiing

## Helpful resources

https://devcenter.heroku.com/articles/mean-apps-restful-api
https://scotch.io/tutorials/making-mean-apps-with-google-maps-part-ii