rContacts

Just a simple example of using Redux and React together. Redux fetches a list of users and passes it to a React component

Version

1.0.0

Installation

Requires Node.js v4+ to run.

$ npm install
Dev Server

$ npm run server
IMPORTANT: The dev server runs on port 8080 by default. If you get an error it may be because that port is in use. If so, go to /node_modules/webpack-dev-server/bin/webpack-dev-server.js and change the 2 instances of "8080" to "8000" or whatever port you want

Then visit http://localhost:8080/ or whatever port you changed it to

Compile

To compile all js to dist/app.bundle.js

$ webpack