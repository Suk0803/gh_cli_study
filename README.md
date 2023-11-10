# gh_cli_study

My gh cli study

# What is gh cli?
gh is Github Command Line tool so check out [here](https://cli.github.com/)

# Install
I used homebrew

```bash
brew install gh
```

# Setup

1. Generate github token [here](https://github.com/settings/tokens)
2. Run `git auth login` to authenticate with your GitHub account. Alternatively, `gh` will respect the `GITHUB_TOKEN` [environment variable](https://cli.github.com/manual/gh_help_environment).
create txt file for save your token.

```bash
vi token.txt
```

and insert your token.\
basic vi commands\
`i` : insert mod\
`esc` : command mod\
`:w` : write\
`:q` : quit\
`:wq` : write and quit

```bash
gh auth login --with-token < token.txt
gh auth status
gh auth setup-git
```
3. Done(perhaps)

