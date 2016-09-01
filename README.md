# little-server-express
Liitle server on express (testing and learning express)

On console run the follows batchs:

npm install

node server.js

# app-example-generator
For app-example-generator
For example, the following creates an Express app named app-example-generator in the current working directory:

$ express app-example-generator

   create : app-example-generator
   create : app-example-generator/package.json
   create : app-example-generator/app.js
   create : app-example-generator/public
   create : app-example-generator/public/javascripts
   create : app-example-generator/public/images
   create : app-example-generator/routes
   create : app-example-generator/routes/index.js
   create : app-example-generator/routes/users.js
   create : app-example-generator/public/stylesheets
   create : app-example-generator/public/stylesheets/style.css
   create : app-example-generator/views
   create : app-example-generator/views/index.jade
   create : app-example-generator/views/layout.jade
   create : app-example-generator/views/error.jade
   create : app-example-generator/bin
   create : app-example-generator/bin/www
Then install dependencies:

$ cd app-example-generator
$ npm install
On MacOS or Linux, run the app with this command:

$ DEBUG=app-example-generator:* npm start
On Windows, use this command:

> set DEBUG=app-example-generator:* & npm start
Then load http://localhost:3000/ in your browser to access the app.

The generated app has the following directory structure:

.
├── app.js
├── bin
│   └── www
├── package.json
├── public
│   ├── images
│   ├── javascripts
│   └── stylesheets
│       └── style.css
├── routes
│   ├── index.js
│   └── users.js
└── views
    ├── error.jade
    ├── index.jade
    └── layout.jade

7 directories, 9 files
