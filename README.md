# inconai website

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
And install the dependencies:
```
bundle install
```

Then start the webserver:
```
bundle exec jekyll serve
```
Now you can navigate to [http://127.0.0.1:4000](http://127.0.0.1:4000) in your web browser.
