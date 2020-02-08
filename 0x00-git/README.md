# Git
Git is a version control software. Every developer should know how to use it.

## Resources
[basic explanation](https://rogerdudler.github.io/git-guide/index.es.html)

## Commands
- `git init` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
- `git clone <url_of_repository>` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
- `git status` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
- `git add` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)

        - `git add .` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
        - `git add -A` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
- `git commit -m <"msg">` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
- `git push` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x00)
        - `git push <branch_name>`
        - `git push origin --delete <branch_name>`
- `git checkout -b <new_name>` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x01)
        - `git checkout <branch_name>`
- `git branch` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x01)
        - `git branch -a`
        - `git branch -d`
        - `git branch -u origin/<remote_branch>`
- `git pull` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x01)
        - `git pull <branch_name>`
- `git fetch` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x01)
- `git reset` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x02)
        -  `git reset [--mixed] HEAD~1`
        - `git reset --soft HEAD~1`
        - `git reset --hard HEAD~1`
 - `git config` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x02)
	 - `git config --get remote.origin.url`
	 - `git config --global user.name <"name">`
	 - `git config --global user.email <"my_email">`
- `git log` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x02)
- `git diff <branch_A > <branch_B>` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x02)
- `git merge <branch>` [🡆](https://github.com/kael1706/my-library/tree/master/0x00-git/pages/0x02)

### How can I undo the last commit in Git?
pd: in this situation the commit was made before doing push origin master
- If you want to keep the local changes:
`git reset [--mixed] HEAD~1`
- If you also do not want to load the commit (just move the head to the previous one):
`git reset --soft HEAD~1`
- And if you don't want to keep them (and return to the state of the previous commit, in practice, destroy the last commit completely as if it never existed):
`git reset --hard HEAD~1`

### How can I undo all local changes and commits?
you can bring the latest version of the server and point to your main local copy in this way:
`git fetch origin; git reset --hard origin/master`

## Authors

 - [Kael1706](https://github.com/kael1706) Carlos Daniel Cortez

## License
[MIT](https://github.com/kael1706/my-library/blob/master/LICENSE "LICENSE")

