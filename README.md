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

Download required gems, install Bourbon & Bourbon Neat in the scss directory, create a localhost with project name (myapp.dev), compile sass, concat js and livereload the browser when changes are made to any file.

    bundle install && cd scss && bourbon install && neat install && cd .. && powder link && guard

Just make sure you have the Livereload browser extension installed and you have clicked the icon to enable it.

## Bower

Bower packages are pulled into the `/js/components/` directory using the `.bowerrc` file.

#### To add a package

	bower install {{name of package}} or {{github repo url}}

## Guard Concat

Edit `Guardfile` to add the js files you want to concat and in which order.