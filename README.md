# angular-chat

Prerequisites
Download Node and npm
angular cli npm install -g @angular/cli
npm install to install all our node dependencies

In the Development Server,

Run ng serve for a dev server. Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.
Run npm run server it follows Twelve-Factor for handling environment variables listed below
PUSHER_APP_ID
PUSHER_APP_KEY
PUSHER_APP_SECRET
DIALOG_ACCESS_TOKEN
e.g PUSHER_APP_ID=[appId] node server.js then POST http://localhost:2000/message or POST http://localhost:2000/join

or Create a .env file with the above variables above, like so

PUSHER_APP_ID="APP_ID"
PUSHER_APP_KEY="APP_KEY"
PUSHER_APP_SECRET="APP_SECRET"
DIALOG_ACCESS_TOKEN="CLIENT_ACCESS_TOKEN"
and run the below in your terminal

node server.js
