# Straightup

Straightup is a skeleton for quickly starting a new static site. [Gulp](http://gulpjs.com/) to concatenate and minify JS files, compress images, compile [SASS](http://sass-lang.com/), recompile assets when changes are detected, and a few other useful helpers. It also runs [BrowserSync](http://www.browsersync.io/) so you can see your changes instantly across multiple devices. Straightup utilizes [Bower](http://bower.io/) to grab front-end libraryies like jQuery. [Yeoman](http://yeoman.io/) scaffolds the application, by writing the Culp configuraltion and pulling our Gulp tasks and Bower dependencies. Straightup comes packaged with [Bourbon](http://bourbon.io/) + [Neat](http://neat.bourbon.io/) + [Bitters](http://bitters.bourbon.io/), providing you with plenty of mixins and variables/extends to give you a jump start on your site.

## Installing Dependencies

You need to have [Node JS](https://nodejs.org), Yeoman, Bower, and Gulp installed for the dependencies to work. Installers for Node JS can be found [here](http://nodejs.org/download/).

### Installing Yeoman:

```shell
npm install -g yo
```

### Installing Bower:

```shell
npm install -g bower
```

### Installing Gulp:

```shell
npm install -g gulp
```

## Installing Project

cd into your project folder and run the following commands 

```shell
bower install
npm install
```

## Watching files and running a dev server

```shell
gulp serve
```

This will run a server for the project that can be accessed at [http://localhost:9000](http://localhost:9000). Changes to files will tell Gulp to automatically rebuild the site. Gulp will also run and compile SASS to CSS , and compile JS when it detects changes to any of these types of files.

## Building the site

```shell
gulp
```

This command will compile all assets, compress images, and compile/minify JS and then build the site to the /dist directory. This directory can then be pushed to your remote site.

I'm still working out changing the relative file paths. Update to come by 3/27.