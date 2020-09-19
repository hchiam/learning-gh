# Learning `gh`: GitHub CLI

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Example workflow all using `gh`: <https://github.blog/2020-09-17-github-cli-1-0-is-now-available>

<https://cli.github.com>

**To create this repo on a Mac:**

```bash
# Make sure you have Xcode installed and updated.
brew install github/gh/gh
gh repo create learning-gh --public
```

**Other commands I like:**

```bash
gh repo clone
gh repo fork

gh issue list --repo hchiam/in-browser-style-linter
gh issue close 1
gh issue reopen 1
gh issue create

gh pr create
gh pr status
```
