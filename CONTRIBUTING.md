# Contributing to SpaceHolder

I'd love to have your help improving SpaceHolder! If you'd like to pitch in, you can do so in a number of ways:

1. Look through open [Issues](https://github.com/jgarber623/spaceholder.cc/issues).
1. Review any open [Pull Requests](https://github.com/jgarber623/spaceholder.cc/pulls).
1. [Fork SpaceHolder](#get-set-up-to-contribute) and fix an open Issue or add your own feature.
1. File new Issues if you have a good idea or see a bug and don't know how to fix it yourself. _Only do this after you've made sure the behavior or problem you're seeing isn't already documented in an open Issue._

I definitely appreciate your interest in (and help improving) SpaceHolder. Thanks!


## Installation

SpaceHolder is written in [Ruby](https://www.ruby-lang.org/en/) (version 2.2.3) using [Sinatra](http://www.sinatrarb.com/). Development dependencies are managed using the [Bundler](http://bundler.io/) gem.

I manage Ruby versions with [rbenv](https://github.com/rbenv/rbenv). I'd recommend you do the same or use a similar Ruby version manager ([chruby](https://github.com/postmodern/chruby/) or [RVM](https://rvm.io/) come to mind). Once you've installed Ruby 2.2.3 using your method of choice, install the project's gems by running:

```sh
bundle install
```

…from the root of the project. To start the app locally in development mode, run:

```sh
bundle exec shotgun
```

This will fire up a server and you'll have the app running locally at `http://localhost:9393/`.


## Get set up to contribute

Contributing to SpaceHolder is pretty straightforward:

1. Fork the SpaceHolder repo and clone it.
1. Install development dependencies by running `bundle install` from the root of the project.
1. Create a feature branch for the issue or new feature you're looking to tackle: `git checkout -b your-descriptive-branch-name`.
1. _Write some code!_
1. Commit your changes: `git commit -am 'Add some new feature or fix some issue'`.
1. Push the branch to your fork of SpaceHolder: `git push origin your-descriptive-branch-name`.
1. Create a new Pull Request and I'll give it a look!


## Code Style

Code styles are like opinions: Everyone's got one and yours is better than mine. Here's how SpaceHolder should be written:

- Use hard tabs for indentation in HTML, CSS, and JavaScript. Use two-space indentation in Ruby.
- No trailing whitespace and blank lines should have whitespace removed.
- Prefer single quotes over double quotes unless interpolating.
- Follow the conventions you see in the existing source code as best as you can.

SpaceHolder's formatting guidelines are defined in the `.editorconfig` file which uses the [EditorConfig](http://editorconfig.org/) syntax. There are [a number of great plugins for a variety of editors](http://editorconfig.org/#download) that utilize the settings in the `.editorconfig` file. Using EditorConfig will make your time spent coding a little bit easier.

Your bug fix or feature addition won't be rejected if it runs afoul of any (or all) of these guidelines, but following the guidelines will definitely make everyone's lives a little easier.