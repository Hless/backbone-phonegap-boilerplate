
Backbone + Ponegap Boilerplate
==============================

This boilerplate template is a fork of the popular Backbone Boilerplate specifically aimed at PhoneGap projects. In the development and building process all URLs are made relative to fully support the file protocol.

During development the code can be hosted on localhost:8080 using a simple webserver. Start the webserver by executing `node server`. Make sure you keep the server running in an active terminal. The webserver is mainly used for the requirejs text plugin, which requires text files (the underscore templates) to be server over HTTP.

By building the project (execute `grunt`), javascript and template files will be merged and compressed into a single source. After building make sure your application works under the file protocol. Your build will be located in the `dist/` folder.

More info will be provided later...