# Learning `gh`: GitHub CLI

Just one of the things I'm learning. <https://github.com/hchiam/learning>

Example workflow all using `gh`: <https://github.blog/2020-09-17-github-cli-1-0-is-now-available>

More info: <https://cli.github.com>

**NOTE:** do _NOT_ run `yarn add gh` _NOR_ `npm install gh` because doing so will install [node-gh/`gh`](https://www.npmjs.com/package/gh) instead of what you actually want: [GitHub's official `gh` cli](https://github.com/cli/cli)

**To create this repo on a Mac:**

```bash
# Make sure you have Xcode installed and updated.
brew install gh
gh repo create learning-gh --public
```

**Other commands I like:**

```bash
gh repo create --template learning-template learning-...

gh repo clone
gh repo fork

gh issue list --repo hchiam/in-browser-style-linter
gh issue close 1
gh issue reopen 1
gh issue create

gh pr create
gh pr status
```

**To get 2fa to work with gh cli, try this:**

https://github.com/node-gh/gh/issues/450#issuecomment-490530739

**To create a new repo from a template repo, all from the CLI:**

https://stackoverflow.com/questions/62630485/is-it-possible-to-create-a-new-git-repository-from-a-template-only-using-the-com
