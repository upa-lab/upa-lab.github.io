

Initial setup on macOS:

```
brew install rbenv
rbenv init
rbenv install $(echo .ruby-version)

# re-open the shell to enble rbenv
bundle install
```

Run:

```
bundle exec jekyll serve
```

