# seekatar.github.io
Public website for Howard P. Wardinkle

https://howardpwardinkle.github.io/

## Jekyll

[Doc](https://jekyllrb.com/docs/)
[Tutorial](https://jekyllrb.com/docs/step-by-step/01-setup/)

```bash
jekyll serve --livereload
```

After installing Ruby 3.0, Jekyll, and Bundler, I had to install the webrick gem to get the site to build.

```bash
bash: /home/jim/gems/bin/bundle: /usr/bin/ruby2.7: bad interpreter: No such file or directory

gem install bundler

/usr/bin/env: ‘ruby2.7’: Not a directory
gem install jekyll bundler


bundle add webrick
```

```bash
bundle install
gem build

# restricts Ruby to use gems in Gemfile
bundle exec jekyll serve --livereload
```

[Starting Theme](https://tianqi.name/jekyll-TeXt-theme/)
[On Github](https://github.com/kitian616/jekyll-TeXt-theme)

[Liquid Doc](https://shopify.github.io/liquid/tags/iteration/)

[Original Theme Readme](text_README.md)

[Gif Converter](https://ezgif.com/)