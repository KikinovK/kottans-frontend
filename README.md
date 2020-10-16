
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

improved understanding:
* `git checkout "name commit"`
* HEAD^, HEAD~n(n - quantity commits), HEAD^n(n - number brunch)
* `git rebase`
* `git cherry-pick`


![Screenshoot "Learn Git branching - complited"](/task-git-intro/learn_git_branching_base.png "Learn Git branching - complited")
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

