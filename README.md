# github-learning


**pull a specific fork** <br>
```
git clone official git_repo
git remote add other_username other_gitlink  # add new remote with specific fork located at other_gitlink
git fetch other_username    # fetch this new remote
git checkout -b my_own_branch   #create a new branch
```
  

**add new files and submit**<br>
git add .  <br>
git commit -m 'msg'


**add code** <br>
\`\`\`python <br>
code snippet <br>
\`\`\`<br>
like this<br>
```python
def func():
  print 'hallo'
```


**\*\* and bold** <br>
\*\* should be close to the following words that needs to be bold. both from starrting to the end


**git log**<br>
check the log hisotry

**git branch**<br>
check the current branch


**git sync local repo with remote repo** <br>
git reset --hard HEAD
git clean -f -x -d -n





**git upload existing project**<br>
1.in github.com, create empty repository, get gitlink: https://github.com/username/xxxx.git  <br>
2. in local direction, find the directory you want to upload(whether a common folder, or a folder with existing github repo downloaded from other user)<br>
git add .  (-f) <br>
git commit -m 'xxxx'<br>
3. add remote repo<br>
git remote add origin https://github.com/username/xxxx.git  <br>
4. push to master<br>
git push origin master


git ls-files  
git rm -r --cached .

 






