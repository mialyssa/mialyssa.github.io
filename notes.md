## Notes regarding build and developing

### Important pages

../**_config.yml** : 
../assets/bower_comp/(b/s/t)/**bootstrap.css** : 
../_sass/**_devlopr.scss** : 

../_includes/
- **about-me.html** : 
- **about-me-temp.html** : 
- **hero.html** : 

### Building page for testing (Windows): 

To work locally with windows machine, follow this commands. You might need to download and install [ruby (with devkit)](https://www.ruby-lang.org/en/downloads/) and [git](https://git-scm.com/downloads).

```s
$ ruby -v 
(ruby 3.1.2p20 (2022-04-12 revision 4491bb740a) [universal.x86_64-darwin21])

$ gem install jekyll bundler

$ bundler -v
Bundler version 2.3.23

$ bundle update
$ bundle install
$ bundle exec jekyll -v 
jekyll 4.2.2

$ bundle exec jekyll serve --livereload
```

If you are running into permission issues running bundler, try the following:

```s
$ sudo rm -rf _site
$ bundle update
$ bundle install
$ bundle exec jekyll serve
```
Start the server locally at http://127.0.0.1:4000/ or http://localhost:4000/
