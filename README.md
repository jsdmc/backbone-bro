backbone-bro
============

Chrome extension for backbone developers

Usage
=====
Bro quickly links you between the markup you see and the backbone view object what sits behind - without being forced to find a corresponding script and debug it. Click on any html element, and see its view in the sidebar, model of the view and all the properties.

Also for convenience, when u inspect some html u can use "_bbbro_view" variable from console - it will give you a quick programmatic access to the selected view.


Features
========
- detects backbone V 1.0.0
- backbone views highlighter
- backbone views sidebar inspector

![ScreenShot](https://raw.github.com/bubenshchykov/backbone-bro/master/screenshot.png)

Installation
===========
Chrome -> Settings -> Extensions -> mark "developer mode" checkbox -> Load unpacked extension -> select a dir with BBBro

Todo
=======
- support other backbone versions
- when highlighing a view show its constructor - could be used as project documentation
- move view inspection from sidebar to a separate tab (like network, scripts etc)
- create "Backbone events" tab what will track all the event hell
- maybe let the plugin start detecting the backbone only if page had ?bbbro path - don't do any js for other pages
- All the suggestions and pull requests are More Than Welcome! :)

