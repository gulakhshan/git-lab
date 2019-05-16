// homework 1

1. Gulakshans-MacBook-Pro:git-lab gula$ git --version
    git version 2.21.0
2.  user.namen=Gulakhshan
     user.email= gh824514@0hio.edu

3. Gulakshans-MacBook-Pro:~ gula$ git --help
    usage: git [--version] [--help] [-C <path>] [-c <name>=<value>]
    [--exec-path[=<path>]] [--html-path] [--man-path] [--info-path]
    [-p | --paginate | -P | --no-pager] [--no-replace-objects] [--bare]
    [--git-dir=<path>] [--work-tree=<path>] [--namespace=<name>]
    <command> [<args>]
    
    These are common Git commands used in various situations:
    
    start a working area (see also: git help tutorial)
    clone      Clone a repository into a new directory
    init       Create an empty Git repository or reinitialize an existing one
    
    work on the current change (see also: git help everyday)
    add        Add file contents to the index
    mv         Move or rename a file, a directory, or a symlink
    reset      Reset current HEAD to the specified state
    rm         Remove files from the working tree and from the index
    
    examine the history and state (see also: git help revisions)
    bisect     Use binary search to find the commit that introduced a bug
    grep       Print lines matching a pattern
    log        Show commit logs
    show       Show various types of objects
    status     Show the working tree status
    
    grow, mark and tweak your common history
    branch     List, create, or delete branches
    checkout   Switch branches or restore working tree files
    commit     Record changes to the repository
    diff       Show changes between commits, commit and working tree, etc
    merge      Join two or more development histories together
    rebase     Reapply commits on top of another base tip
    tag        Create, list, delete or verify a tag object signed with GPG
    
    collaborate (see also: git help workflows)
    fetch      Download objects and refs from another repository
    pull       Fetch from and integrate with another repository or a local branch
    push       Update remote refs along with associated objects
    
    'git help -a' and 'git help -g' list available subcommands and some
    concept guides. See 'git help <command>' or 'git help <concept>'
    to read about a specific subcommand or concept.
    
4. Gulakshans-MacBook-Pro:git-lab gula$ git status
On branch master

No commits yet

Untracked files:
(use "git add <file>..." to include in what will be committed)

README.md
answers.md

nothing added to commit but untracked files present (use "git add" to track)

5. Gulakshans-MacBook-Pro:git-lab gula$ git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)

new file:   README.md

Untracked files:
(use "git add <file>..." to include in what will be committed)

answers.md

6. Gulakshans-MacBook-Pro:git-lab gula$ git status
On branch master

No commits yet

Changes to be committed:
(use "git rm --cached <file>..." to unstage)

new file:   README.md
new file:   answers.md



7. Gulakshans-MacBook-Pro:git-lab gula$ git commit -m "initial commit"
[master (root-commit) 26f5dfb] initial commit
2 files changed, 54 insertions(+)
create mode 100644 README.md
create mode 100644 answers.md

8. Gulakshans-MacBook-Pro:git-lab gula$ git log
commit 26f5dfb910452a72083f25cd438d14df8f46865e (HEAD -> master)
Author: gula <gh824514@0hio.edu>
Date:   Thu May 16 07:45:30 2019 -0400

initial commit

9.  README.md    initial commit    26 minutes ago
     answers.md    initial commit    26 minutes ago
         
10. my name is Gulakhshan Hamad
      my user name is Gulakhshan
      my email adress is gh824514@ohio.edu
      
11. Gulakshans-MacBook-Pro:git-lab gula$ git push 
To https://github.com/gulakhshan/git-lab.git
! [rejected]        master -> master (fetch first)
error: failed to push some refs to 'https://github.com/gulakhshan/git-lab.git'
hint: Updates were rejected because the remote contains work that you do
hint: not have locally. This is usually caused by another repository pushing
hint: to the same ref. You may want to first integrate the remote changes
hint: (e.g., 'git pull ...') before pushing again.
hint: See the 'Note about fast-forwards' in 'git push --help' for details.
Gulakshans-MacBook-Pro:git-lab gula$ 

12. yes, they were reflected 
my name is Gulakhshan Hamad
my user name is Gulakhshan
my email adress is gh824514@ohio.edu
cs 2400,section 107
13. Gulakshans-MacBook-Pro:git-lab gula$ ls -a
       .git        answers.md
       README.md    git-lab-2
       
14. yes, 
       Gulakshans-MacBook-Pro:git-lab gula$ g++ -Wall git-lab-program.cc
       Gulakshans-MacBook-Pro:git-lab gula$ ./a.out
       Hello Git!!
15. yes, it is online
            .gitignore    Initial commit    28 minutes ago
            README.md    Initial commit    28 minutes ago
            git-lab-program.cc   hello    2 minutes ago 







        

