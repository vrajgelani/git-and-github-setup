# git-and-github-setup for all laptop and desktop
install git --> https://git-scm.com/install/windows<br>
add your config into git<br>
open git bash into computer<br>
paste below cmd:<br>
git  config --global --unset user.name<br>
git  config --global --unset user.email<br>
git  config --global  user.name "vrajgelani"<br>
git  config --global user.email "vrajgelani1@gmail.com"<br>
5.check your git config(paste below cmd into gitbash)
git config --list <br>
6.check your email and username in given output<br>
7.check a project folder into computer(ex.news-website)<br>
8.join your folder with github <br>
9.go to github website(login first)<br>
10.create a new repo (check for new btn into dashbord-green color btn)<br>
11.give a name to repo(ex.news-website)<br>
12.click button --> create a repo (green botton)<br>
13.find the link that start with --> git remote add origin --> copy that whole line <br>
14.open your vs code --> open terminal (check the menu the option terminal --> new terminal) --> first check last word(ex./news-website>)<br>
15.paste the copy link(repo link) --> close the terminal<br>
16.create files, edit files, delete files into your folder
17.open terminal and give below cmd one by one:
git add .
git commit -m "give a msg"
git push origin main (main --> branch name {check your working brach first and after tha t write the branch name})
18.repeat the cycle
edit files --> git add . --> git commit -m "give a msg" --> git push origin main --> edit files
