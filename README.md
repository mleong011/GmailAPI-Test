## To use Gmail API 
* Here is a helpful link that helped my set up gmail api:  https://www.fullstacklabs.co/blog/access-mailbox-using-gmail-node (most of below steps are from this link)
* First, create a project in the Google Developers Console. Visit https://console.developers.google.com/ and log in, then click on Select a project > NEW PROJECT.
* Enable the Gmail API Library
    * Navigate to the Library, search for the Gmail API and enable it.
    * you can also enable it through here: https://developers.google.com/gmail/api/quickstart/nodejs
* Configure OAuth Consent Screen
    * Before creating the credentials, configure the OAuth consent screen by clicking on the button CONFIGURE CONSENT SCREEN. 
* Create Credentials
    * In the left menu, click on Credentials > CREATE CREDENTIALS, and select OAuth client ID. (I selected desktop app as the application type)
    * You should be able to see the new credentials under the OAuth 2.0 Client IDs section. Click on the download icon to download the credentials file. <strong> Then rename it to credentials.json. </strong>
<em> I ran into some errors here with the generated credentials.json and it works with the syntax used in the uploaded credentials.json, so you can just enter your credentials in credentials.json file uploaded</em> 

* Run the following commands to install the libraries using npm:
<em>Make sure to be in the express-backend folder </em>

`npm install googleapis@39 --save`

* Lastly, Run the sample using the following command:

`node .`

* Here are some resources I found for using the api:
    * https://www.npmjs.com/package/node-gmail-api
    * https://blog.mailtrap.io/send-emails-with-gmail-api/
(haven't looked through them throughly, but plan to)
# gmailAPI-test
