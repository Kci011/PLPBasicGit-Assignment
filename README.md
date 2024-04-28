# PLPBasicGit-Assignment


$ cd desktop


$ mkdir PLPBasicGitAssignment
mkdir: cannot create directory ‘PLPBasicGitAssignment’: File exists

$ cd PLPBasicGitAssignment/


$ git init
Initialized empty Git repository in C:/Users/YOU/Desktop/PLPBasicGitAssignment/.git/


$ git status
On branch master

No commits yet

nothing to commit (create/copy files and use "git add" to track)


$ git remote add origin <https://github.com/Kci011/PLPBasicGit-Assignment.git>
bash: syntax error near unexpected token `newline'


$ git remote add origin https://github.com/Kci011/PLPBasicGit-Assignment.git


$ touch hello.txt


$ ls
hello.txt


$ code .




$ git add hello.txt

$ git commit -m "Add hello.txt with a greeting"
[master (root-commit) 2475b55] Add hello.txt with a greeting
 1 file changed, 1 insertion(+)
 create mode 100644 hello.txt


$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Kci011/PLPBasicGit-Assignment.git'


$ git status
On branch master
nothing to commit, working tree clean


$ git pull origin main
remote: Enumerating objects: 3, done.
remote: Counting objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
Unpacking objects: 100% (3/3), 876 bytes | 32.00 KiB/s, done.
From https://github.com/Kci011/PLPBasicGit-Assignment
 * branch            main       -> FETCH_HEAD
 * [new branch]      main       -> origin/main
fatal: refusing to merge unrelated histories

$ --allow-unrelated-histories
bash: --allow-unrelated-histories: command not found


$ git push -u origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/Kci011/PLPBasicGit-Assignment.git'


$ git remote add https://github.com/Kci011/PLPBasicGit-Assignment.git
usage: git remote add [<options>] <name> <url>

    -f, --[no-]fetch      fetch the remote branches
    --[no-]tags           import all tags and associated objects when fetching
                          or do not fetch any tag at all (--no-tags)
    -t, --[no-]track <branch>
                          branch(es) to track
    -m, --[no-]master <branch>
                          master branch
    --[no-]mirror[=(push|fetch)]
                          set up remote as a mirror to push to or fetch from



$ git commit -m "Add hello.txt with a greeting"
On branch master
nothing to commit, working tree clean


$ git remote add origin 'https://github.com/Kci011/PLPBasicGit-Assignment.git'
error: remote origin already exists.

$ git push -u origin master
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 242 bytes | 80.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
remote:
remote: Create a pull request for 'master' on GitHub by visiting:
remote:      https://github.com/Kci011/PLPBasicGit-Assignment/pull/new/master
remote:
To https://github.com/Kci011/PLPBasicGit-Assignment.git
 * [new branch]      master -> master
branch 'master' set up to track 'origin/master'.
