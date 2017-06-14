
---



You can now switch back to your work-in-progress branch on issue 53 and proceed with your work:

`$ git checkout issue53`

`$ vim contact.html`

`$ git commit -am "done mapping the hub"`



Notice in the figure below how the master branch, after deleting the hotfix branch, still points at the same place.



![](/assets/back.png)



        **The issue53 branch moves forward independently **



**NB: **

      Since a branch is an isolated working environment, the work you did in the hotfix branch is not contained in the files in your issue-53 branch. To pull the work in requires an explicit merge of the master branch into the issue-53 branch. Preferably \(my take\), you can delay the integration of those changes until you decide to pull the issue-53 branch back into master \(the more stable branch or least questionable branch\).

