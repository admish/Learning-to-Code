# Version Control

Version control is the practice of managing and tracking changes to code using software tools. Also known as Source Control, it allows you to revert changes,  and save your code remotely. There are only a very small number of commands you will need when starting off, but it's also very powerful and multiple teams can work on the same project at once with git.

Git, Mercurial, and SVN are some of the most popular, with [Git dominating almost 75%](https://www.openhub.net/repositories/compare) of the industry. I have seen SVN used on older systems over the years, but no one has expected me to learn it, and only knowing how to use Git has never held me back. Only knowing SVN and not Git will dehibilitate you until you learn Git. [RogerDudler](https://rogerdudler.github.io/git-guide/) on GitHub, has a very helpful guide that should help you getting started.

It's not a requirement to use the [terminal](Command_Line.md) with Git, and there are several GUI clients available. It is still a good idea to become familiar with the terminal for troubleshooting.

### Common Commands

For a beginner working alone, learning these commands first should be enough to get started.

* Add - Add all file changes to the stage and prepare them to commit
* Commit - Create a save point, with a brief comment on what changed or why you're saving
* Push - Send your last commit to the remote location
* Pull - Tell your local copy to update and download any changes
* Init - Initialize a new repository in a folder that may be empty, or already be a project in process.
* Clone - Connect to a remote repository and download a copy on your local machine



### Online Git Repo's

You do not need to setup an account on an online site to store your code. It's a good thing to do so you have a backup, but not required to use some of the most powerful features Git offers. Private repositories aren't free on a lot of sites, and depending on your code, you may not want to push it to a public repository. 

**ALWAYS be VERY cautious to NEVER push code with a password or private key to a public repo.**

* [GitHub](https://github.com/)
* [GitLab](https://about.gitlab.com/)
* [BitBucket](https://bitbucket.org/) by Atlassian
* [Launchpad](https://launchpad.net/) by Canonical
* [SourceForge](https://sourceforge.net/)
* [Cloud Source Repositories](https://cloud.google.com/source-repositories) by Google
* [AWS CodeCommit](https://aws.amazon.com/codecommit/) by Amazon
* [Phabricator](https://www.phacility.com/phabricator/)
* [Beanstalk](https://beanstalkapp.com/)
* [Rhodecode](https://rhodecode.com/)
* [CodeGiant](https://codegiant.io/)
* [trac](https://trac.edgewall.org/)
* [teknik](https://www.teknik.io/)

#### Self-Hosted Private Git Repo's
* [GitLab](https://about.gitlab.com/)
* [Gogs](https://gogs.io/)
* [Gitea](https://gitea.io/)
* [Allura](https://allura.apache.org/) by Apache


### Other Commands
GitHub has a useful [cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf) 

- git init
- git add
- git push
- git pull
- git commit
- git clone
- git remote
- git merge
- git fetch
- git config
- git checkout
- git status
- git revert
- git reset
- git rebase
- git show
- git stash
- git diff
- git log
- git branch
- git cherry-pick
- git tag