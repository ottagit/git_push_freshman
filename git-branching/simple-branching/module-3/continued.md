
---



After deploying the fix, you can safely switch back to the issue 53 branch and carry on with the work you had started earlier. You can optionally delete the hotfix branch \(as you no longer need it\) - the master branch points at the same place. See the figure below:

![](/assets/pointer.png)

**The master branch points at the same point as the hotfix branch after the merge**

You can safely delete the hotfix branch with the `-d` option to `git branch`

`$ git branch -d hotfix`

The above option is considered "safe" because Git prevents the deletion of a branch if there are unmerged changes.

To forcefully delete a branch, use the -D option instead:

`$ git branch -D hotfix`

The command above ignores unmerged changes and deletes the branch anyway. Use this command when you want to permanently throw away all of the commits associated with a given line of development.

