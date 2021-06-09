# Website

## Install

1. Install Ruby+Devkit: [https://rubyinstaller.org/](https://rubyinstaller.org/)
2. Run the ridk install step on the last stage of the installation wizard.
3. Install Jekyll and Bundler using `gem install jekyll bundler`
4. Check if Jekyll has been installed properly: `jekyll -v`
5. Run `bundle install` within the root directory.

## Developing

To serve the application while working: `jekyll serve`

## Building

In order to build the jekyll site run: `jekyll build`

Then copy the contents within the `_site` directory to your server.
