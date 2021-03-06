# Git em projetos solos ou em equipes

```
  <type>[optional scope]: <description>
  [optional body]
  [optional footer]
```

- ## Types
  
  - 'build':Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
  - 'ci': Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)
  - 'chore': If doesnt match the others, this is the choice
  - 'docs': Documentation only changes
  - 'feat': A new feature
  - 'fix':  A bug fix 
  - 'perf': A code change that improves performance
  - 'refactor / improvement': A code change that neither fixes a bug nor adds a feature
  - 'revert': Back to some old version 
  - 'style': Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)
  - 'test': Adding missing tests or correcting existing tests

- ## Footer

- 'BREAKING CHANGE': Major change, that makes something not work, partial or total, compare to the previews version.

## Alias

`.gitconfig
[alias]
  st = status
  ci = commit
  br = branch
  co = checkout
`
```terminal
    alias ga='git add'
    alias gc='git commit -v'
    alias gd='git diff'
    alias gst='git status'
    alias gco='git checkout'
    alias gcm='git checkout master'
    alias gb='git branch'
    alias gbr='git branch --remote'
    alias gup='git pull --rebase'
    alias gp='git push'
    alias gpsup='git push --set-upstream origin $(git_current_branch)'
```
