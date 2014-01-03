bootstrap3_ie7_ie8
==================

Bootstrap 3 has been built 'responsive first'. This means that the grid has made heavy use of media queries which are not supported in IE8 ord older versions.

This results in the these browsers displaying a single column mobile layout. Not ideal if you need to support older versions of IE.

Bootstrap 3 - Amends for IE7 / IE8 will make the grid look acceptable for IE7 and IE8

Setup
-----

bootstrap3_ie7_ie8 requires [Node.js][node] 0.10+.

You'll also need [Grunt][grunt] to be installed globally , you can do this with `npm install -g grunt-cli`.

You'll then need to clone this repo locally and install dependencies with `npm install`.

Now start the application to watch for any changes to LESS files and will compile the CSS.

```sh
$ grunt
```

Open up any less file in this project and save the file. This will kick off a compile.

Open up the index.html file in a browser.

Take a look at this file in IE7 or IE8.


To use in your own Bootstrap 3 based project
--------------------------------------

Copy the ie8and.less file into your folder where the LESS files are.

Add line to the bootstrap file at the end to import this file.

Place a conditional statement on the body of your markup (see example in index.html in this repo)

Take a look at your site in IE7 or IE8.

License
-------

[Copyright 2014 Perry Harlock](LICENSE.txt).  
bootstrap3_ie7_ie8 is licensed under the [GNU General Public License 3.0][gpl].

[gpl]: http://www.gnu.org/licenses/gpl-3.0.html
[node]: http://nodejs.org/
[grunt]: http://gruntjs.com/