> Make a new GitHub release from git metadata

**Note** This is an extension of conventional-changelog/conventional-gihub-releaser. Check out the original repo [here](https://github.com/conventional-changelog/conventional-github-releaser)

[Set up a token first](#setup-token-for-cli).

## Setup token for cli

[Create a new token](https://github.com/settings/tokens/new) and set your environment variable `CONVENTIONAL_GITHUB_RELEASER_TOKEN` to the token you just created. You can google [How to set environment variable](https://www.google.com.au/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=how%20to%20set%20environment%20variable). The scopes for the token you need is `public_repo` or `repo` (if you need to access private repos). [More details](https://developer.github.com/v3/oauth/#scopes).

### Recommended workflow

1. Make changes
2. Commit those changes
3. Make sure Travis turns green
4. Bump version in `package.json`
5. Commit `package.json` files
6. Tag
7. Push
8. `conventionalGithubReleaser`

Remember to use `-p atom` to parse our atom commit style and `--draft` to publish a draft release.

## License

MIT © [Steve Mao](https://github.com/stevemao)
