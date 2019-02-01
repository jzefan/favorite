## Java enum 
  1. https://blog.scottlogic.com/2016/07/28/java-enums-how-to-use-them-smarter.html
  2. https://howtodoinjava.com/java/enum/guide-for-understanding-enum-in-java/

## Git merge 
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
## Java Spring 
  1. https://marcin-chwedczuk.github.io/spring-transactional-cheat-sheet (很好地解释了transactional)
  2. https://cloud.tencent.com/developer/ask/78013 (一个中文回答）
  
## Feign
  1. Error: `Caused by: java.lang.IllegalStateException: RequestParam.value() was empty on parameter 0`. 解决：在@RequestParam 增加方法名
```java
@GetMapping(value = "/add")
ResponseEntity<ResultData> add(@RequestParam @NotNull Integer a, @RequestParam @NotNull Integer b);
``` 
```java
@GetMapping(value = "/add")
ResponseEntity<ResultData> add(@RequestParam("a") @NotNull Integer a, @RequestParam("b") @NotNull Integer b);
```
  
## Good Q&&A on stackoverflow
 - [Avoid unchecked assignment in a map with multiple value types?](https://stackoverflow.com/questions/22467645/avoid-unchecked-assignment-in-a-map-with-multiple-value-types)
 
## 个人博客
 - https://yezhwi.github.io/ 微服务，java等


