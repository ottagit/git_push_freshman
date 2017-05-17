We've noted that

`git checkout testing`

moves \_HEAD \_to point to the testing branch. The significance of this is seen when making another commit

`vim my_test.rb`

`git commit -am 'yet another commit'`

in which the branch that HEAD points to moves forward with the commit as shown in the figure below:





![](/assets/imp9.png)



               _**See, HEAD is smart enough not to lag behind**_

