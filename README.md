# This is my local Repo <br>
Learning git Part 2 <br>

<h3> Init Command </h3> <br>

1) git init        --> Init is used to crate a new git Repo <br>
2) git remote add origin <-link >    --> Here <b> remote</b> is github Repository with name as Origin <br>
   ex: git remote add origin https://github.com/way2masoom/localrepo.git </br>
3) git remote -v        --> to verify the repo(Is the Repository is present or not) <br>
4) git branch           --> To see the Branch <br>
5) git branch -M <Name>  ---> To rename the <i>branch name</i> </br>
6) git push origin main  --> To push <i>Local</i> files to <i>Remote</i> Repo <br>
6) git push -u origin main  --> To push <i>Local</i> files to <i>Remote</i> Repo Here <b> -u </b> is used to set upstream || Means if you want to work in same Repo the you can make shortcut using -u, the simply you can Type < Git Push > To save your time. <br>


<h3> Branch Command </h3> <br>
1) git branch           --> To see the Branch <br>
2) git branch -M <Name>  ---> To rename the <i>branch name</i> </br>
3) git checkout <-branch name->  ---> To switch from one brach to another branch <b>
4) git checkout -b <-New branch name-> ---> To crate new branch <br>
5) git checkout -d <-branch name-> ---> To Delete branch <br>

<h3> Merge </h3> <br>
There two way to merge the code <br>
# By command line 
1) git diff <-branch name --> It compare our working directly with staging area </br>
ex: git diff main
2) git merge <-branch name->   --> To merge Two branch <br>

# By Create a PR(Pull Request)
crate a PR and review the code and merge the cod <br>