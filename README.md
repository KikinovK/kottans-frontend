
# Kottans-frontend course

## Stage 0. Self-Study

### General
 0. [Git Basics](#Git_and_GitHub)
 1. [Linux CLI and Networking](#Linux_Command_Line_HTTP_Tools)
 2. [Git Collaboration](#GitHub_and_collaboration)

 ***
 
## <a name="Git_and_GitHub">Git and GitHub</a>

### Version control with Git
Learned an useful things:

* connect the code editor to git, it became convenient to describe commits, name tags `git config --global core.editor "code --wait"` 
* viewing the list of commits and its branches:
  * `git log`
    * press `q` to quit 
  * `git log --oneline`
  * `git log --stat`
  * `git log -p`
  * `git diff`
  * `git log --decorate`
  * `git log --oneline --decorate`
  * `git log --oneline --decorate --graph --all`

![Screenshoot "Version control with Git - complited"](/task-git-intro/udacity_version_control_with_git.png "Version control with Git - complited")

### Learn Git branching

was improved understanding:
* `git checkout "name commit"`
* HEAD^, HEAD~n(n - quantity commits), HEAD^n(n - number brunch)
* `git rebase`
* `git cherry-pick`


![Screenshoot "Learn Git branching - complited"](/task-git-intro/learn_git_branching_base.png "Learn Git branching - complited")
![Screenshoot "Learn Git branching  remote - complited"](/task-git-collaboration/task-git-intro.png "Learn Git branching remote - complited")
***               
## <a name="Linux_Command_Line_HTTP_Tools">Linux, Command Line, HTTP</a>
### Linux survival
#### Command_Line
* `ls` - list the contents of a directory
  * `ls -l` - long list 
* `cd` - change directory
* `pwd` - print working directory
* `mkdir` - create directory 
* `cp` - copy file
* `mv` - move and rename file
* `rm` - remove file
* `rmdir` - remove directory
* `groups` - group users
* `chmod ugo+rwx file name` - change mode

Did not saw command `touch`(create file) in the course

![Screenshoot "Linux survival quiz nubmer 1 - complited"](/task-linux-cli/quiz_number_1.png "Linux survival quiz nubmer 1")
![Screenshoot "Linux survival quiz nubmer 2 - complited"](/task-linux-cli/quiz_number_2.png "Linux survival quiz nubmer 2")
![Screenshoot "Linux survival quiz nubmer 3 - complited"](/task-linux-cli/quiz_number_3.png "Linux survival quiz nubmer 4")
![Screenshoot "Linux survival quiz nubmer 4 - complited"](/task-linux-cli/quiz_number_4.png "Linux survival quiz nubmer 4")

### HTTP

![http url structure](/task-linux-cli/http1-url-structure.png "http url structure")

* GET: fetch an existing resource.
* POST: create a new resource. 
* PUT: update an existing resource.
* DELETE: delete an existing resource.

## <a name="Git_Collaboration">GitHub Collaboration</a>
### GitHub & Collaboration
Learned to create remote repositories 

tutorial example [https://github.com/KikinovK/my-travel-plans](https://github.com/KikinovK/my-travel-plans)
used commands like this
* `git remote` to manage a remote repository
  * `git remote -v` list remote repositores
  * `git remote add <shortname> <URL>`
* `git push <shortname> <branch>` to send changes
* `git pull <shortname> <branch>` to retrisve and automatically merge updates
* `git fetch <shortname> <branch>` to retrisve updates

* `git shortlog` 
* `git shortlog -s -n`
* `git log --author=<name author>`
* `git log --grep=<filter>`

**Create Pull Request**

_fork_ a remote repo in GitHub -> local `git clone <name forked repo>`-> `git checkout -b <name new branch` -> commit to new branch -> `push <shortname  repo> <name new branch>` -> press _New pull request_ or _Compare & pull request_ in GitHub -> add comment and press _Create pull request_

![Screenshoot "Github & collaboration - complited"](/task-git-collaboration/Github_and_collaboration.png "Github & collaboration")

### Learn Git branching

`git push <shortname  repo> <source>:<recipient>`

![Screenshoot "Learn Git branching  main - complited"](/task-git-collaboration/learn_git_branching_base.png "Learn Git branching main - complited")

![Screenshoot "Learn Git branching  remote - complited"](/task-git-collaboration/learn_git_branching_remote.png "Learn Git branching remote - complited")
