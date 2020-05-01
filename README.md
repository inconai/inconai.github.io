# incon.ai website


### Installation
To run this website locally, go to your favorite git cloning folder and clone this repo:

```
git clone https://github.com/inconai/inconai.github.io.git
```
or with ssh:
```
git clone git@github.com:inconai/inconai.github.io.git
```

then go into the repo:
```
cd inconai.github.io
```
Make sure you have at least a version 2 of ruby installed:
```
ruby --version
> ruby 2.X.X
```
Otherwise [install Ruby 2.1.0 or higher](https://www.ruby-lang.org/en/downloads/).

Then install the bundler:
```
gem install bundler
```

### Install the jekyll dependencies:
```
bundle install
```

### Running the jekyll webserver

Then start the webserver:
```
bundle exec jekyll serve
```
Now you can navigate to [http://127.0.0.1:4000](http://127.0.0.1:4000) in your web browser.


###Using Gulp to build:

- `gulp` the default task that builds everything
- `gulp watch` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory
