When you switch back to the _master_ branch by running the command

`git checkout master`,

the command:

1. moves the _HEAD_ pointer back to point to the master branch
2. reverts the files in your working directory back to the snapshot that \_master \_points to

This also means that subsequent changes made from this point will diverge from an older version of the project. It essentially rewinds the work you've done in your testing branch temporarily so that you can take a different direction.

---

![](/assets/import10.png)



           _**HEAD moves to a another branch on a checkout**_

---



