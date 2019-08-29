# sagittarius
Sagittarius - a github bot that auto-review and comment code in new opened PR's

<center><img src="https://github.com/Gherciu/sagittarius/blob/master/sagittarius-logo.png" alt="sagittarius" width="150px" height="150px"/></center>

#### Getting started

In your repo create a `.sagettariusrc.js` config file.
All available config settings are available [here](http://github.com). Or see a example of minimal config [here](http://github.com).

Globally install sagittarius cli.
`npm i -g sagittarius`

Then start the bot in background mode.
` sagittarius start`

#### Config settings:
- `repo` - URL to github repo [see usage](http://github.com)
- `validateCommitMessage` - a function that validate config message [see usage](http://github.com)


#### Cli commands:
- `start` - to initialize a background job who listen and validate new PR's

---

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## Author

**@Gherciu/sagittarius** © [GHERCIU](https://github.com/Gherciu), Released under the [MIT](./LICENSE) License.<br>
Authored and maintained by GHERCIU with help from contributors ([list](https://github.com/Gherciu/sagittarius/contributors)).

#### If you like this repository star⭐ and watch👀 on [GitHub](https://github.com/Gherciu/sagittarius)
