# Point guard

A boilerplate for [Sass](http://sass-lang.com/) and JavaScript using [Guard](https://github.com/guard/guard), [Bourbon](http://bourbon.io) and [Bourbon Neat](http://neat.bourbon.io).

- - - 

### Prerequisites

[Ruby](http://www.ruby-lang.org), [rvm](https://rvm.io), [pow](http://pow.cx), [livereload browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)

### Setup

Clone the repo

    git clone https://github.com/joshfry/point-guard.git

Rename the project, for example, "myapp"

    mv point-guard myapp

cd into "myapp"

    cd myapp

Download required gems, install Bourbon & Bourbon Neat in the scss directory, create a localhost with project name (myapp.dev), compile sass, concat js and livereload the browser when changes are made to any file.

    bundle install ; cd scss ; bourbon install ; neat install ; cd .. ; powder link ; guard

Just make sure you have the Livereload browser extension installed and you have clicked the icon to enable it.
