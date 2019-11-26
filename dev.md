# Development Manual

## Project

- `yarn | yarn install`

## vsce flow

- `yarn global add vsce`
- `yarn login (publisher name)`
- `vsce package` | `vsce publish`

## Git flow

- `git add .`
- `git cz`
- `yarn release [-- --release-as [major | minor | patch]]`
- `git push --follow-tags origin master && vsce publish`
