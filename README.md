# Terminal DRILL

### This repository is made for extra-practie my Command line (Terminal) skills.
There will be all kind of exercises with cmnder.

### git status
- untracked - logs, temp, etc
- tracked - files inneed
  - modified - changed, but not commited
  - commited - fixed by git
  - staged - files added to index, prepeared to commit

### Cheatsheet
N# | command | discription
:---:| --- | ---
1 | git config --system | whole system
2 | git config --local | repo only
3 | git config --global | user only
4 | git log | commits list
5 | git log | commit list
6 | -la | list all 
7 | -ma | no messege all
8 | git show | [#commit]
9 | git log -p | log with extra info
10 | git restore [file] | *modified* back to last commit
11 | git diff --staged | diff for added *staged*
12 | git restore --staged [file] | back from index *staged*
13 | git rm --cached [file] | rm from *untracked*
14 | git branch -d [branch] | delete fully merged br
15 | git branch -D [branch] | delete UNmerged branch
16 | git branch -b [branch] | new branch + redirect to it
17 | git pull/push origin master | while not config
18 | git pull | git fetch + git merge
19 | git push --set-upstream | + origin master
20 | git tag [..] | lightweight
21 | git tag -a [..] -m ".." | annotated
22 | git push origin [..] | push tag
23 | git push --tags | push all tags

### Create new repo
- `echo "# Postman" >> README.md`
- `git init`
- `git add README.md`
- `git commit -m "first commit"`
- `git branch -M main`
- `git remote add origin git@github.com:v-las/Postman.git`
- `git push -u origin main`

### First time git config
- `git config --global user.name "Your name here"`
- `git config --global user.email "your_email@example.com"`
- `ssh-keygen -t rsa -C "your_email@example.com"`
- `clip < ~/.ssh/id_rsa.pub`
- `eval 'ssh-agent -s'`
- `ssh-add`
- `ssh -T git@github.com`

<details>
<summary>Yo Dawg, I heard you like spoilers</summary>
  <details>
  <summary>So I put a spoiler on your spoiler</summary>
    <details>
    <summary>So you can drive while</summary>
    Snape kills Dumledore
      
      Aaahh! You know this joke already, I'm so proud of you!~
<img src="https://marriednetworth.com/wp-content/uploads/2018/05/xzibit_2466.jpeg" alt="Snoop Dogg" width="70%" height="70%">
  </details>
</details>
