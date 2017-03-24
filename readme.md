# Innovation Edge's Git Guide: Zero to 100

This guide is to provide newcomers with a brief set of readings to develop a general understanding of Git and our current Git strategy in place. Thus, by no means is this a comprehensive guide to Git, but a means to be effective when getting started with Git.

## Required Readings
### Git Introduction
- **[A Short Git Guide](http://rogerdudler.github.io/git-guide/)**

### Git Strategies
> This will be our branching strategy, which is widely used among popular GitHub OOS projects. In addition, it's rather simple, yet flexible. Even better, it's pure bliss with continuous delivery and CI.

- **[Introduction to GitHub Flow](https://guides.github.com/introduction/flow/)**
- *Optional: [A deeper dive of Github Flow](http://scottchacon.com/2011/08/31/github-flow.html)*

Once you review the articles above, you'll be wondering how does this fit inline with us? You can review the diagram below, which provides a concrete a sample git history spanning 2 sprints.

[Diagram of GitHub Flow Revised for IE Sprints](https://cisco-ie.github.io/ie-git-guide/)

### Git Practices
> A easy, yet effective practice that everyone should be following, which will make it far easier to comprehend Git histories.

- **[How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)**

## Useful Things
### Automated Tooling
- **[GitMagic](https://app.gitmagic.io/)**  
Automate rule checking, a [contribution.json](https://github.com/cisco-ie/ie-git-guide/blob/master/contributing.json) is located within this repo, which falls inline with Chris Beam's article.

### Git Aliases
Include these alias in your shell's `.rc` file, and you'll have access to these useful git aliases.

```bash
alias gs='git status '
alias ga='git add '
alias gb='git branch '
alias gc='git commit'
alias gp='git pull'
alias gps='git push'
alias gpsu='git push --set-upstream origin'
alias gd='git diff'
alias got='git '
alias get='git '
alias glog='git log --graph --decorate --pretty=oneline --abbrev-commit --all --date=local'
```

### Reference Sheets
- **[GitHub Cheat Sheet](https://github.com/tiimgreen/github-cheat-sheet)**
- **[Visual Reference to Git Commands](http://marklodato.github.io/visual-git-guide/index-en.html)**
- **[Most Commonly Used Git Commands and Tricks](https://github.com/git-tips/tips)**

## Extra Credit
This material is not required but is still relevant.
- **[Git Book](https://git-scm.com/book/en/v2)**  
One of the best resources on git. This is a lot of content and not necessary for day-to-day, but you will become very proficient with this material.

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
