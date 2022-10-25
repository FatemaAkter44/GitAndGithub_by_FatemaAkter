fatemaakter@Fatemas-MacBook-Pro documents % git clone 
https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git
Cloning into 'GitAndGithub_by_FatemaAkter'...
warning: You appear to have cloned an empty repository.
fatemaakter@Fatemas-MacBook-Pro documents % touch Git.txt Github.txt
fatemaakter@Fatemas-MacBook-Pro documents % ls
Git.txt
GitAndGithub_by_FatemaAkter
Github.txt
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % pwd
/Users/fatemaakter/documents
fatemaakter@Fatemas-MacBook-Pro documents % pwd 
/Users/fatemaakter/documents
fatemaakter@Fatemas-MacBook-Pro documents % ls
Git.txt
GitAndGithub_by_FatemaAkter
Github.txt
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % cp Git.txt 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter a
fatemaakter@Fatemas-MacBook-Pro documents % lsls
zsh: command not found: lsls
fatemaakter@Fatemas-MacBook-Pro documents % ls
Git.txt
GitAndGithub_by_FatemaAkter
Github.txt
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % rm Git.txt
fatemaakter@Fatemas-MacBook-Pro documents % rm Github.txt
fatemaakter@Fatemas-MacBook-Pro documents % ls
GitAndGithub_by_FatemaAkter
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % cd GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % touch Git.txt GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo "Git is a DevOps tool used for source 
code management. It is a free and open-source version control system used to handle small to very large 
projects efficiently. Git is used to tracking changes in the source code, enabling multiple developers to 
work together on non-linear development." > git.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cat Git.txt
Git is a DevOps tool used for source code management. It is a free and open-source version control system 
used to handle small to very large projects efficiently. Git is used to tracking changes in the source 
code, enablinfatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo "Git is a DevOps tool 
used for source code management. It is a free and open-source version control system used to handle small 
to very large projects efficiently. Git is used to tracking changes in the source code, enabling multiple 
developers to work together on non-linear development." > Git.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cat Git.txt
Git is a DevOps tool used for source code management. It is a free and open-source version control system 
used to handle small to very large projects efficiently. Git is used to tracking changes in the source 
code, enabling multiple developers to work together on non-linear development.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_Fafatemaakter@Fatemas-MacBook-Pro 
GitAndGithub_by_FatemaAkter % echo "Git is used for source code management, it's an open-source DevOps 
tool, and GitHub is a Git repository hosting platform. It is used widely for control and collaboration 
purposes. The platform is a place for storing code which is intellectual property, so it is very 
important to make it a safe space." > GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cd ..
fatemaakter@Fatemas-MacBook-Pro documents % ls
GitAndGithub_by_FatemaAkter
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % pwd
/Users/fatemaakter/documents
fatemaakter@Fatemas-MacBook-Pro documents % ls
GitAndGithub_by_FatemaAkter
apiCall.csv
apiCall1.csv
assignment4
assignment4.zip
awsfile
fatemaakter@Fatemas-MacBook-Pro documents % cd GitAndGithub_by_FatemaAkter 
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % nano README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % 

fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
add README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
commit -m "this is the first try of assignmrnt 5 v1"
[main (root-commit) 3608336] this is the first try of assignmrnt 5 
v1
 3 files changed, 100 insertions(+)
 create mode 100644 Git.txt
 create mode 100644 GitHub.txt
 create mode 100644 README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
branch -M main
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
remote add origin 
https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git 
error: remote origin already exists.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
push -u origin branch main
error: src refspec branch does not match any
error: failed to push some refs to 
'https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git'
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
push -u origin main       
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.39 KiB | 1.39 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mkdir 
temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cd 
/Users/fatemaakter/Documents/assignment4
fatemaakter@Fatemas-MacBook-Pro assignment4 % ls
Screen Shot 2022-10-08 at 1.17.55 PM.png
Screen Shot 2022-10-08 at 1.20.28 PM.png
Screen Shot 2022-10-08 at 1.26.08 PM.png
Screen Shot 2022-10-08 at 1.40.09 PM.png
assignment4_text_file.rtf
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp Screen Shot 
2022-10-08 at 1.17.55 PM.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
cp: Screen: No such file or directory
cp: Shot: No such file or directory
cp: 2022-10-08: No such file or directory
cp: at: No such file or directory
cp: 1.17.55: No such file or directory
cp: PM.png: No such file or directory
fatemaakter@Fatemas-MacBook-Pro assignment4 % ls
Screen Shot 2022-10-08 at 1.26.08 PM.png
Screen Shot 2022-10-08 at 1.40.09 PM.png
assignment4_text_file.rtf
p1.png
p2.png
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp p1.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp p2.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro assignment4 % cd 
fatemaakter@Fatemas-MacBook-Pro ~ % 
fatemaakter@Fatemas-MacBook-Pro ~ % ls
API		Downloads	Music		abc.txt
Applications	IdeaProjects	Pictures	qaae_b2202
Desktop		Library		Postman		testFolder
Documents	Movies		Public
fatemaakter@Fatemas-MacBook-Pro ~ % cd Documents 
fatemaakter@Fatemas-MacBook-Pro Documents % ls
GitAndGithub_by_FatemaAkter	assignment4
apiCall.csv			assignment4.zip
apiCall1.csv			awsfile
fatemaakter@Fatemas-MacBook-Pro Documents % cd 
GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		README.md	p2.png
GitHub.txt	p1.png		temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/GitAndGithub_by_FatemaAkter/p1.png 
//GitAndGithub_by_FatemaAkter/temp
mv: rename /GitAndGithub_by_FatemaAkter/p1.png to 
//GitAndGithub_by_FatemaAkter/temp: No such file or directory
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/p1.png 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		README.md	temp
GitHub.txt	p2.png
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/p2.png 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cd 
temp 
fatemaakter@Fatemas-MacBook-Pro temp % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro temp % nano .gitignore
fatemaakter@Fatemas-MacBook-Pro temp % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

nothing added to commit but untracked files present (use "git add" 
to track)
fatemaakter@Fatemas-MacBook-Pro temp % git add .gitignore
fatemaakter@Fatemas-MacBook-Pro temp % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	p1.png
	p2.png

fatemaakter@Fatemas-MacBook-Pro temp % git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
fatemaakter@Fatemas-MacBook-Pro temp % git pull
Already up to date.
fatemaakter@Fatemas-MacBook-Pro temp % git checkout -b [differences]     
zsh: no matches found: [differences]
fatemaakter@Fatemas-MacBook-Pro temp % git log --oneline
3608336 (HEAD -> main, origin/main) this is the first try of 
assignmrnt 5 v1
fatemaakter@Fatemas-MacBook-Pro temp % git branch differences
fatemaakter@Fatemas-MacBook-Pro temp % git branch -a
  differences
* main
  remotes/origin/main
fatemaakter@Fatemas-MacBook-Pro temp % git checkout differences
A	temp/.gitignore
Switched to branch 'differences'
fatemaakter@Fatemas-MacBook-Pro temp % cd ..
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
Features of Git
Tracks history.
Free and open source.
Supports non-linear development.
Creates backups.
Scalable.
Supports collaboration.
Branching is easier.
Distributed development. >> Git.txt 
Features of Git
zsh: command not found: Tracks
zsh: command not found: Free
zsh: command not found: Supports
zsh: command not found: Creates
zsh: command not found: Scalable.
zsh: command not found: Supports
zsh: command not found: Branching
zsh: command not found: Distributed
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ceho 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
zsh: command not found: ceho
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
GitHub is a code hosting platform for version control and 
collaboration. It lets you and others work together on projects from 
anywhere. This tutorial teaches you GitHub essentials like 
repositories, branches, commits, and pull requests. >> GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % 

finished untill 17---------------------------------------------




d
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % 

fatemaakter@Fatemas-MacBook-Pro 
GitAndGithub_by_Fafatemaakter@Fatemas-MacBook-Pro 
GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
init
Reinitialized existing Git repository in 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/.git/
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
add .
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
status
On branch main

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
	new file:   Git.txt
	new file:   GitHub.txt
	new file:   README.md

fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
add README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
commit -m "this is the first try of assignmrnt 5 v1"
[main (root-commit) 3608336] this is the first try of assignmrnt 5 
v1
 3 files changed, 100 insertions(+)
 create mode 100644 Git.txt
 create mode 100644 GitHub.txt
 create mode 100644 README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
branch -M main
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
remote add origin 
https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git 
error: remote origin already exists.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
push -u origin branch main
error: src refspec branch does not match any
error: failed to push some refs to 
'https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git'
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
push -u origin main       
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 16 threads
Compressing objects: 100% (5/5), done.
Writing objects: 100% (5/5), 1.39 KiB | 1.39 MiB/s, done.
Total 5 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/FatemaAkter44/GitAndGithub_by_FatemaAkter.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mkdir 
temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cd 
/Users/fatemaakter/Documents/assignment4
fatemaakter@Fatemas-MacBook-Pro assignment4 % ls
Screen Shot 2022-10-08 at 1.17.55 PM.png
Screen Shot 2022-10-08 at 1.20.28 PM.png
Screen Shot 2022-10-08 at 1.26.08 PM.png
Screen Shot 2022-10-08 at 1.40.09 PM.png
assignment4_text_file.rtf
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp Screen Shot 
2022-10-08 at 1.17.55 PM.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
cp: Screen: No such file or directory
cp: Shot: No such file or directory
cp: 2022-10-08: No such file or directory
cp: at: No such file or directory
cp: 1.17.55: No such file or directory
cp: PM.png: No such file or directory
fatemaakter@Fatemas-MacBook-Pro assignment4 % ls
Screen Shot 2022-10-08 at 1.26.08 PM.png
Screen Shot 2022-10-08 at 1.40.09 PM.png
assignment4_text_file.rtf
p1.png
p2.png
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp p1.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro assignment4 % cp p2.png 
/Users/fatemaakter/documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro assignment4 % cd 
fatemaakter@Fatemas-MacBook-Pro ~ % 
fatemaakter@Fatemas-MacBook-Pro ~ % ls
API		Downloads	Music		abc.txt
Applications	IdeaProjects	Pictures	qaae_b2202
Desktop		Library		Postman		testFolder
Documents	Movies		Public
fatemaakter@Fatemas-MacBook-Pro ~ % cd Documents 
fatemaakter@Fatemas-MacBook-Pro Documents % ls
GitAndGithub_by_FatemaAkter	assignment4
apiCall.csv			assignment4.zip
apiCall1.csv			awsfile
fatemaakter@Fatemas-MacBook-Pro Documents % cd 
GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		README.md	p2.png
GitHub.txt	p1.png		temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/GitAndGithub_by_FatemaAkter/p1.png 
//GitAndGithub_by_FatemaAkter/temp
mv: rename /GitAndGithub_by_FatemaAkter/p1.png to 
//GitAndGithub_by_FatemaAkter/temp: No such file or directory
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/p1.png 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		README.md	temp
GitHub.txt	p2.png
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % mv 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/p2.png 
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % cd 
temp 
fatemaakter@Fatemas-MacBook-Pro temp % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter/temp
fatemaakter@Fatemas-MacBook-Pro temp % nano .gitignore
fatemaakter@Fatemas-MacBook-Pro temp % git status
On branch main
Your branch is up to date with 'origin/main'.

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	./

nothing added to commit but untracked files present (use "git add" 
to track)
fatemaakter@Fatemas-MacBook-Pro temp % git add .gitignore
fatemaakter@Fatemas-MacBook-Pro temp % git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   .gitignore

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	p1.png
	p2.png

fatemaakter@Fatemas-MacBook-Pro temp % git push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
fatemaakter@Fatemas-MacBook-Pro temp % git pull
Already up to date.
fatemaakter@Fatemas-MacBook-Pro temp % git checkout -b [differences]     
zsh: no matches found: [differences]
fatemaakter@Fatemas-MacBook-Pro temp % git log --oneline
3608336 (HEAD -> main, origin/main) this is the first try of 
assignmrnt 5 v1
fatemaakter@Fatemas-MacBook-Pro temp % git branch differences
fatemaakter@Fatemas-MacBook-Pro temp % git branch -a
  differences
* main
  remotes/origin/main
fatemaakter@Fatemas-MacBook-Pro temp % git checkout differences
A	temp/.gitignore
Switched to branch 'differences'
fatemaakter@Fatemas-MacBook-Pro temp % cd ..
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % pwd
/Users/fatemaakter/Documents/GitAndGithub_by_FatemaAkter
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
Features of Git
Tracks history.
Free and open source.
Supports non-linear development.
Creates backups.
Scalable.
Supports collaboration.
Branching is easier.
Distributed development. >> Git.txt 
Features of Git
zsh: command not found: Tracks
zsh: command not found: Free
zsh: command not found: Supports
zsh: command not found: Creates
zsh: command not found: Scalable.
zsh: command not found: Supports
zsh: command not found: Branching
zsh: command not found: Distributed
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ceho 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
zsh: command not found: ceho
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
GitHub is a code hosting platform for version control and 
collaboration. It lets you and others work together on projects from 
anywhere. This tutorial teaches you GitHub essentials like 
repositories, branches, commits, and pull requests. >> GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt		GitHub.txt	README.md	temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % >....       
Tracks history.
Free and open source.
Supports non-linear development.
Creates backups.
Scalable.
Supports collaboration.
Branching is easier.
Distributed development. >> Git.txt
Features of Git
zsh: command not found: Tracks
zsh: command not found: Free
zsh: command not found: Supports
zsh: command not found: Creates
zsh: command not found: Scalable.
zsh: command not found: Supports
zsh: command not found: Branching
zsh: command not found: Distributed
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ceho 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
zsh: command not found: ceho
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
One of the biggest advantages of Git is its branching capabilities. 
Unlike centralized version control systems, Git branches are cheap 
and easy to merge. This facilitates the feature branch workflow 
popular with many Git users. Feature branches provide an isolated 
environment for every change to your codebase. >> Git.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % echo 
GitHub is a code hosting platform for version control and 
collaboration. It lets you and others work together on projects from 
anywhere. This tutorial teaches you GitHub essentials like 
repositories, branches, commits, and pull requests. >> GitHub.txt
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % ls
Git.txt         GitHub.txt      README.md       temp
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter %
>> README.md
zsh: parse error near `)'
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % nano 
README.md
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
status
On branch differences
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	new file:   temp/.gitignore

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working 
directory)
	modified:   Git.txt
	modified:   GitHub.txt
	modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	temp/p1.png
	temp/p2.png

fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
add .
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
status
On branch differences
Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   Git.txt
	modified:   GitHub.txt
	modified:   README.md
	new file:   temp/.gitignore
	new file:   temp/p1.png
	new file:   temp/p2.png

fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
comment -m "added a new branch name"          
git: 'comment' is not a git command. See 'git --help'.

The most similar command is
	commit
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
checkout master
error: pathspec 'master' did not match any file(s) known to git
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
checkout main 
M	Git.txt
M	GitHub.txt
M	README.md
A	temp/.gitignore
A	temp/p1.png
A	temp/p2.png
Switched to branch 'main'
Your branch is up to date with 'origin/main'.
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % git 
push -u origin main
branch 'main' set up to track 'origin/main'.
Everything up-to-date
fatemaakter@Fatemas-MacBook-Pro GitAndGithub_by_FatemaAkter % 

