
---



With an urgent fix to make, you create a branch for it, cal it hotfix, where you do your work until it's competed:

`$ git checkout -b hotfix`

`$ vim followers.html.erb`

`$ git commit -am 'add followers feed'`

`[hotfix 3a0874c] add follower feed`

`1 file changed, 13 additions(+)`

![](/assets/fix.png)

**hotfix branch based back at the master branch point**

At this point \(_HEAD_ points to hotfix\), you can run your tests \(more on tests here: [http://agiledata.org/essays/tdd.html](http://agiledata.org/essays/tdd.html)\), make sure the hotfix produces the desired output, and merge it back to the master branch and deploy it to production. Merging is achieved with the `git merge` command:

`$ git checkout master`

`$ git merge hotfix`

`Updating f42c576..3a0874c`

`Fast-forward`

Your change is now in the commit pointed to by the master branch and is ready for deployment.

