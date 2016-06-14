Starter repo to kickstart your ES2015 (ES6) based JavaScript project.

## Quickstart

Fork this repo to your account and then run the following:-

    git clone https://github.com/YOURNAME/es2015-starter.git

    # Feel free to rename the directory and remove .git
    cd es2015-start
    npm install

The following NPM packages will be installed:-
    
    babel-core
    babel-loader
    babel-preset-es2015
    html-webpack-plugin
    http-server
    webpack

Once all the packages installed, run the command:-

    npm run transpile

That will invoke `webpack` and transpile your ES2015 to ES5 JavaScript. The output will be in `dist/` directory.
The generated `index_bundle.js` will be automatically injected into `index.html`.

Run `npm run server` will start an HTTP server at port 8080. Load `http://localhost:8080/` and open up the developer
console. You should see the "hello world" message displayed.
