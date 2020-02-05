A Github Pages template for academic websites. This was forked from the [Academicpages github repository](https://github.com/academicpages/academicpages.github.io).

#### To start building your own website, you can fork this repository
#### Note: if you are using this repo and now get a notification about a security vulnerability, delete the Gemfile.lock file. 

### Run locally:

1. Fork and clone the repository
1. Make sure you have ruby-dev, bundler, and nodejs installed: `sudo apt install ruby-dev ruby-bundler nodejs`
1. Run `bundle clean` to clean up the directory (no need to run `--force`)
1. Run `bundle install` to install ruby dependencies. If you get errors, delete Gemfile.lock and try again.
1. Run `bundle exec jekyll liveserve` to generate the HTML and serve it from `localhost:4000` the local server will automatically rebuild and refresh the pages on change.

Feel free to send an issue or a pull request
