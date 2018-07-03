# State of the Browser

Static site for the State of the Browser 2018 website.

The website is viewable at <https://2018.stateofthebrowser.com>.

# TODO

- finish HTML and SCSS for Schedule page
- add more information (like lunch) to Venue page
- figure out how to make the design more interesting?
- add interaction through better hover states, transitions, animations
- ensure ServiceWorker and Manifest are as we want them
- figure out how to go Push notifications

# Build pipeline

The project uses [Netlify](https://netlify.com) services, which will build and deploy at every push to the `2018` branch into production.

All files can be committed to git.

_If you have any queries please open a ticket or ask in the main Slack channel._

# Development

If you want to contribute, please either fork or branch off the `2018` branch (if you are within the LWS org), and create a PR to merge into `2018`.

Netlify will automatically build a new preview for every PR created, merging will be forbidden if the build doesn't pass.

## Requirements

These are the basic requirements in order to edit and build the project:

### Bundler and Jekyll

The way to install Bundler and Jekyll is with `gem` through [Ruby](https://www.ruby-lang.org/en/downloads/):

    $ gem install bundler jekyll

## Building the project

### For development purposes

The following command will build the project for development:

    $ bundle exec jekyll start

You then need to open a new window in your browser. Automatic refresh of your bwoser will happen every time any source file is modified.

The project can be accessed at <http://localhost:3000>.
