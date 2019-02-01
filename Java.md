## Java enum 
  1. https://blog.scottlogic.com/2016/07/28/java-enums-how-to-use-them-smarter.html
  2. https://howtodoinjava.com/java/enum/guide-for-understanding-enum-in-java/

## git merge 
  - https://stackoverflow.com/questions/5601931/what-is-the-best-and-safest-way-to-merge-a-git-branch-into-master
  - https://git-scm.com/book/en/v2/Git-Branching-Rebasing (The book is very good!)
  - http://gitready.com/
```git
git checkout master
git pull origin master
git merge test
git push origin master
```
```git
git checkout master
git pull origin master
git merge --squash test
git commit
git push origin master
```
