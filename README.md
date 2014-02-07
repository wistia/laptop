Laptop
======

Wistia Laptop Setup Script

Requirements
------------

### Mac OS X

1) Install a C compiler.

For Mavericks (10.9): run `sudo xcodebuild -license` and follow the instructions
to accept the XCode agreement.  Then run `xcode-select --install` in your
terminal and then click "Install".

2) Set zsh as your login shell:

    chsh -s /bin/zsh

3) Install full Xcode app from app store

Install
-------

### Mac OS X

Read, then run the script:

    zsh <(curl -s https://raw.github.com/wistia/laptop/master/mac)

What it sets up
---------------

* Bundler gem for managing Ruby libraries
* Exuberant Ctags for indexing files for vim tab completion
* Foreman gem for serving Rails apps locally
* Heroku Config plugin for local `ENV` variables
* Heroku Toolbelt for interacting with the Heroku API
* Hub gem for interacting with the GitHub API
* Homebrew for managing operating system libraries (OS X only)
* ImageMagick for cropping and resizing images
* Postgres for storing relational data
* macvim for text editing
* mysql for wistia database magic
* Qt for headless JavaScript testing via Capybara Webkit
* Rails gem for writing web applications
* Rbenv for managing versions of the Ruby programming language
* Redis for storing key-value data
* Ruby Build for installing Rubies
* Ruby stable for writing general-purpose code
* The Silver Searcher for finding things in files
* Tmux for saving project state and switching between projects
* Watch for periodically executing a program and displaying the output

It should take less than 15 minutes to install (depends on your machine).

Credits
-------

![thoughtbot](http://thoughtbot.com/assets/tm/logo.png)

Laptop is maintained and funded by [thoughtbot, inc](http://thoughtbot.com/community).
The names and logos for thoughtbot are trademarks of thoughtbot, inc.

Thank you, [contributors](https://github.com/thoughtbot/laptop/graphs/contributors)!

Contributing
------------

Please see [CONTRIBUTING.md](https://github.com/thoughtbot/laptop/blob/master/CONTRIBUTING.md).

License
-------

Laptop is © 2011-2014 thoughtbot, inc. It is free software, and may be
redistributed under the terms specified in the LICENSE file.
