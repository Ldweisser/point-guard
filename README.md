# Point guard

A boilerplate for [Sass](http://sass-lang.com/) and JavaScript using [Guard](https://github.com/guard/guard), [Bourbon](http://bourbon.io) and [Bourbon Neat](http://neat.bourbon.io).

- - - 

### Prerequisites

[Ruby](http://www.ruby-lang.org), [rvm](https://rvm.io), [pow](http://pow.cx), [livereload browser extension](http://feedback.livereload.com/knowledgebase/articles/86242-how-do-i-install-and-use-the-browser-extensions-)

### Setup

`git clone https://github.com/joshfry/point-guard.git` - Clone the repo
`mv point-guard myapp` - Rename the project. For example, "myapp"
`cd myapp` - cd into "myapp"
`bundle install ; cd scss ; bourbon install ; neat install ; cd .. ; powder link ; guard` - the magic

Downloads required gems, installs Bourbon & Bourbon Neat in the scss directory, creates a localhost with project name (myapp.dev), compiles sass, concats js and live reloads the browser when changes are made to any file.

Just make sure you have the Livereload browser extension installed and you have clicked the icon to enable it.
