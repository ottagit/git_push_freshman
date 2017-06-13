While still on branch \_issue53, \_you work on the web app and make some commits. This moves the branch forward, because you have it checked out, i.e., \_HEAD \_points to it.



`$ vim contact.html`

`$ git commit -am "add google map" [issue 53]`



Depicted below is how the \_issue 53 \_branch moves:

![](/assets/bm3.png)

An issue arises from the web app that calls for your immediate attention; it needs a fix. With Git, you don't have to deploy the fox along with the issue 53 changes you just made, and little effort is required to revert those changes before you can apply your fix to what's in production \(the live web, more information here: [https://www.techopedia.com/definition/8989/production-environment](https://www.techopedia.com/definition/8989/production-environment "production environment")\). All that needs to be done is switch back to your master branch.

**NOTE:**

Unless otherwise, it's good practice to branch off your master branch since in most cases this is your most stable branch into which other branches merge.

If your working directory or staging area has uncommitted changes that conflict with the branch you're checking out \(in this case, master\), Git will not let you switch branches. Ensure you have a clean working state when switching branches.

