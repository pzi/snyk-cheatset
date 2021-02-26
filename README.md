# Snyk Cheatset

Snyk cheat sheet as docset for [Dash](http://kapeli.com/dash).

The cheat sheet is based on the
[Snyk CLI Cheatsheet](https://snyk.io/blog/snyk-cli-cheat-sheet/) on the [Snyk Blog](https://snyk.io/blog) and has been extended with content form the Snyk CLI help.

## Convert the cheatset to a docset

```bash
cheatset generate Snyk.rb
```

The [format](https://github.com/Kapeli/cheatset#readmehttps://github.com/Kapeli/cheatset#readme) used to define a cheat sheet is quite simple.

## Contributing

1. Fork this repository
1. Install cheatset: `$ sudo gem install cheatset`  
    **Note:** this requires the Xcode Command Line Tools to be installed.  
    `$ xcode-select --install`
2. Create a branch: `$ git checkout -b my-changes`
3. Generate docset: `$ cheatset generate Snyk.rb`
4. Test the docset in Dash
5. Commit & push your changes
6. Create new Pull Request
