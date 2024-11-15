# Jiffy
A template Jekyll site with wiki functionality

## Development
In order to rebuild the site locally you'll need to:
1. clone the repo
2. install Ruby, Jekyll and Bundler ([guide](https://jekyllrb.com/docs/installation/))
  * Try to match [these versions](https://pages.github.com/versions/) where possible in order to get the same behavior locally as via GitHub. Pay attention to Jekyll and Ruby versions in particular.
  * E.g., MacOS: `brew install ruby@3.3.4` and `echo 'export PATH="/opt/homebrew/opt/ruby@3.3.4/bin:$PATH"' >> ~/.zshrc` and `gem install jekyll -v 3.10.0`
3. run `bundle install`
4. run `bundle exec jekyll serve`  <-- run this each time you want to restart the local server
5. goto http://127.0.0.1:4000
6. run `bundle exec jekyll build` <-- run this to generate _site files without localhost URLs