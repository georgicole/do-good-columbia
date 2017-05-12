# Do Good Columbia

https://rcpl.github.io/do-good-columbia/

Not much to see here yet. So far just a collection of The Good Parts™ of the current Richland Library web site, refactored, cleaned up with new standards. Documentation follows below:

### Human-Readable Color Palette
Based on [great research done by Tom Osborne at Viget](https://www.viget.com/articles/naming-colors)

### SVG UI on a 12-Square Grid
The icon grid (12 units) was adopted from FontAwesome so icons from that set are compatible, but only the necessary icons have been included. The icomoon configuration can be found at [img/ui/Richland Library 2.0.json](/img/ui/Richland Library 2.0.json).

### Flex-First Layouts with Sassless 2
https://github.com/wraybowling/sassless

### Translations
111 languages with Google Translate

### Trackable Updates
with Github, including all data

## Local Setup & Maintenance

### Install
```
gem install jekyll bundler
cd ~/Sites/
git clone git@github.com:RCPL/v3-jekyll.git
cd v3-jekyll
bundle install
```

### Run
```
bundle exec jekyll serve
```

### View
 - Local: [http://localhost:4000](http://localhost:4000)
 - Github: https://rcpl.github.io/v3/

### Update Dependencies or Reinstall
```
bundle update
```

### Admin Panel for Quick Edits (Local Only)
[localhost:4000/admin](http://localhost:4000/admin)
