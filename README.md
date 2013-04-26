# Point guard

A boilerplate for [Sass](http://sass-lang.com/) and JavaScript using [Guard](https://github.com/guard/guard), [Bourbon](http://bourbon.io) and [Bourbon Neat](http://neat.bourbon.io).

- - - 

### Prerequisites

[Ruby](http://www.ruby-lang.org), [rvm](https://rvm.io), [pow](http://pow.cx), [livereload browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)

### Directions

Clone this repo

`git clone https://github.com/joshfry/point-guard.git`

Rename folder with project name

`mv point-guard myapp`

cd into project

`cd myapp`

Download required gems, install Bourbon & Neat, create a localhost with app name (myapp.dev), compile sass, concat js and live reload the browser when changes are made to any file.

`bundle install ; cd scss ; bourbon install ; neat install ; cd .. ; powder link ; guard`
