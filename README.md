# nofap-counter

nofap-counter is a simple nodejs project that keeps track of your nofap count and displays it in a nice looking UI.

Screenshots
----

![Screenshot](https://i.imgur.com/l6Sqviw.png)

Installation & Configuration
----

You can download the latest tarball by clicking [here](https://github.com/maxxarmino/nofap-counter/tarball/master) or latest zipball by clicking  [here](https://github.com/maxxarmino/nofap-counter/zipball/master).

Or even better, you could just git clone it straight from github.

    git clone --depth 1 https://github.com/maxxarmino/nofap-counter.git nofap-counter

First navigate to your installation directory.

    cd nofap-counter
    
You then need to install all the dependencies, you can do this by using npm.

    sudo npm install

After you have all the dependencies installed you need to set the `dayzero` variable on line 13 to the correct date. The format is `YYYYMMDD`, e.g `20151118`.

Usage
----

After the configuration you're ready to start `server.js`.

    sudo node server.js

The server should now be running at `http://localhost:80`
