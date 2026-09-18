# homebrew-tools

A Homebrew tap. One formula so far.

```bash
brew tap toygunchill/tools
brew install shipkit
```

This tap is private, so `brew tap` clones it over your own GitHub credentials —
`gh auth login` once and it works like any other tap.

## shipkit

Holds AI coding agents to a team's pull-request conventions: it writes the
commit message, fills the repo's PR template, opens the pull request against
the right branch, and shows you the change on a local page before any of it
leaves your machine.

Needs Node. Source: https://github.com/toygunchill/shipkit
