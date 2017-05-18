If you go ahead and make further changes then commit, the next commit stores a pointer to the commit that immediately preceded it. After two more commits, your history may look like the figure below

![](/assets/imp6.png)

```
                 _**Git object data for multiple commits**_
```

**Branch Defined**

In Git, a branch is a lightweight movable pointer to one of these commits, with the default name for a branch being _master_. As you initially make commits, Git gives you a master branch that points to the last commit you made. Every time you commit, the master branch moves forward automatically.



_**NB: **_Apart from the fact that it is created when you initialize a repository with `git init` , the 'master' branch is not in any way special and can be manipulated like any other custom branch.

