# Point guard

A boilerplate for Sass and JavaScript.

- - - 

## Read the docs

[Sass](http://sass-lang.com/), [Guard](https://github.com/guard/guard), [Bourbon](http://bourbon.io), [Bourbon Neat](http://neat.bourbon.io), [Livereload](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-), [Bower](http://bower.io)

## Prerequisites

[Ruby](http://www.ruby-lang.org), [rvm](https://rvm.io), [pow](http://pow.cx), [livereload browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-), [node](http://nodejs.org), [npm](https://npmjs.org), [Bower](http://bower.io)

## Setup

Clone the repo

    git clone https://github.com/joshfry/point-guard.git

Rename the project, for example, "myapp"

    mv point-guard myapp

cd into "myapp"

    cd myapp

Download required gems

    bundle install

cd into scss directory
    
    cd scss
    
install Bourbon
    
    bourbon install
    
install Bourbon Neat
    
    neat install
    
Go back to project root
    
    cd ..
    
Install project dependancies with Bower

    bower install
    
Create a webserver with powder using pow to host project files located at myapp.dev

    powder link
    
Run guard to compile sass, concat js and livereload the browser when changes are made to any file

    guard

## The even _easier_ setup

##### Just copy and paste this into your shell

    echo What is the name of your project? ; read NAME ; git clone https://github.com/joshfry/point-guard.git && mv point-guard $NAME && cd $NAME && bundle install && cd scss && bourbon install && neat install && cd .. && bower install && powder link && open http://$NAME.dev && guard

## Bower

Bower packages are installed in the `/js/components/` directory. The configuration is handled with the `.bowerrc` file.

To add a new package

    bower install <name-of-package> --save

To uninstall a package

    bower uninstall <name-of-package> --save

## Guard Concat

Edit `Guardfile` to add the js files you want to concat and in which order.


## Testing another setup.. don't use

	echo What is the name of your project? ; read NAME ; git clone https://github.com/joshfry/point-guard.git && mv point-guard $NAME && cd $NAME && bundle install && cd scss && bourbon install && neat install && cd .. && bower install && powder link && subl . && open . && open http://$NAME.dev && guard
