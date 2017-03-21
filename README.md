Template for optimized Jekyll site or blog with Grunt
=============

1.  Install [Node.js](www.nodejs.org) and [Ruby](https://www.ruby-lang.org/)
2.  Run `gem install bundler`
3.  Install 'grunt-cli' and 'bower' globally with `npm install -g grunt-cli bower`
4.  `$cd` to the directory and run `bundle install`
5.  Run `npm install` to install the necessary "npm" dependencies
6.  Then run `bower install` to install the front-end dependencies

Install Bourbon:

`gem install bourbon`

`bourbon install`

Add `@import 'bourbon/bourbon';` to main.scss file.

NOTE: Bourbon must be installed in same directory as main.scss

Install Neat:

`gem install neat`

`neat install`

Add `@import 'neat/neat';` to main.scss file. Place below `@import 'bourbon/bourbon'`

NOTE: Neat must be installed in same directory as main.scss


7.  **That's all. Your template is ready**
