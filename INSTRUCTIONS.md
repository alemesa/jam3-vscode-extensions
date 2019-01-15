# README

## Jam3 Extension Pack

This was bootstrapped with Yeoman

Using this:
`npm install -g yo generator-code`

### To publish

[Official Instructions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

- Run `npm install -g vsce`
- Get an azure account
- Get personal access token
- Create a publisher => `vsce create-publisher (publisher name)`
- Login to publisher => `vsce login (publisher name)`
- Enter your token

`vsce package` => Prepare package for publishing

`vsce publish` => Publish to the marketplace

How to update your package with `Semver`

`vsce publish minor` => `2.0.0` to `2.0.1`

`vsce publish major` => `3.0.0` to `3.1.0`

### Good to know

- The icon provided in `package.json` may not be an SVG.
- The badges provided in the `package.json` may not be SVGs unless they are from trusted badge providers.
- Image URLs in `README.md` and `CHANGELOG.md` need to resolve to https URLs.
- Images in `README.md` and `CHANGELOG.md` may not be SVGs unless they are from trusted badge providers.

### Contributions Guide
