Jekyll Frontend Kit
===================
[![Build Status](https://travis-ci.org/LandRegistry/jekyll-frontend-kit.svg?branch=master)](https://travis-ci.org/LandRegistry/jekyll-frontend-kit)

Made with [Jekyll](http://jekyllrb.com/), [Bootstrap](http://getbootstrap.com/), [Bootswatch](http://bootswatch.com/) & [Font Awesome](http://fortawesome.github.io/Font-Awesome/).

Tested with [HTML Proofer](https://github.com/gjtorikian/html-proofer).

Deployed by [Travis CI](https://travis-ci.org/matthew-shaw/matthew-shaw.github.io).

Hosted by [MaxCDN](http://www.bootstrapcdn.com/) and [GitHub Pages](https://pages.github.com/).

### Getting started
Requires [Ruby](https://www.ruby-lang.org/en/downloads/) and [RubyGems](http://rubygems.org/pages/download).
```
git clone git@github.com:LandRegistry/jekyll-frontend-kit.git
cd jekyll-frontend-kit
bundle install
bundle exec jekyll serve
```

### Running tests
This is the same script that Travis runs during the build, run this locally before pushing to avoid broken builds:
```
./script/cibuild
```

### Deploying with Travis
```
travis enable
git commit -a -m "super awesome commit message"
git push
```

### Changing themes
Change the ```theme``` setting in ```_config.yml``` to any of the [Bootswatch](http://bootswatch.com/) theme names and restart the server.
