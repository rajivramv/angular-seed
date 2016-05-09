# angular-seed
An angular-gulp project seed

## Pre-requisities
* [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
* [Node 0.10.x +](https://nodejs.org/en/download/)
* [Ruby](https://www.ruby-lang.org/en/documentation/installation/)
* [Sass](http://sass-lang.com/install)

## Steps to run
1. Clone the repository `git clone https://github.com/rajivramv/angular-seed.git`
2. `cd angular-seed` and `npm install` will install the node and bower dependencies.
3. `npm start` builds the output `www` folder and starts a file server and rest server.

## Note
There are several gulp tasks that you can use during development. These commands are evoked as `gulp <command>` (if gulp is installed globally), for example, `gulp clean-dist`. Some of the useful commands are listed below. Have a look at `gulpfile.js` for others.

1. `clean-dist` - cleans/deletes the `www` folder
2. `compile-sass` - compiles all the sass code into a single css file. The css file (`index.css`) will be located inside a `css` folder at the same level of the main `scss` folder
3. `build-dist` - builds the full project
4. `serve-dist` - starts the file and rest server
5. `watch` - watches for any changes in the `src` folder and runs the appropriate gulp task that updates the `www` folder
