# Instant-Messenger
This repo will be a guide on how to build a instant messaging web application using JavaScript and SInch API.

###Create account
Sign up at https://www.sinch.com/

#Quick start help
Visit https://www.sinch.com/dashboard/#/quickstart

#Get the API key and copy it

#Editing part
-Open the IMsample.js file
and edit the following

//*** Set up sinchClient ***/
sinchClient = new SinchClient({
	applicationKey: 'Application_key',
	capabilities: {messaging: true},
	startActiveConnection: true,
	
Edit the Application key with the API you have copied and save it.

*Run it on your web browser and use it.
