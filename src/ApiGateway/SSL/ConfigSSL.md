﻿# How to configure SSL on your local dev machine

Certificate in this folder is a default certificate for development, nicely provided by IIS Express.
You can find the same thing on your local dev machine within Local computer Personal certificates, but thumbprint could bi different.

* Install the cerificate
* Execute commands in PS script
* Configure your WebApp to use correct port
* ???
* PROFIT!

Now you can have secured access with, for example, this URL: https://localhost:12345/users/3/albums?page=1.     

You can also run the service without SSL support. It's default mode.

To run with SSL enabled, change App.Config parameter ssl to true. Otherwise use http protocol.