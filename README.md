# planning-poker

## Prerequisites

You will need [Leiningen][] 2.0.0 or above installed.

[leiningen]: https://github.com/technomancy/leiningen

## Compiling Assets
Run:

    lein cljsbuild once

To automatically compile assets when you change a file, run:

    lein cljsbuild auto


## Running

To start a web server for the application, run:

    lein run

Then, load http://localhost:8080 in your web browser.

If you use ngrok, make sure your web server configuration allows you to access the app at http://127.0.0.1:8080.

## Licenses
PLANNING POKER ® is a registered trademark of Mountain Goat Software, LLC
Sequence of values is (C) Mountain Goat Software, LLC

Copyright © 2015
