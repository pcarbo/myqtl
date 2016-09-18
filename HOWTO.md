# How to create another "fork" of this repository

1. Create a new project on github (e.g., "myqtl").

2. Make a local copy of the old project: `git clone
   git@github.com:pcarbo/qtl.git myqtl`

3. In your local copy of the old project, update the URL for the
   *origin* remote to point to the new project: `git remote set-url
   origin git@github.com:pcarbo/myqtl.git`
   
4. Push the changes to the new remote, designating the new repository as being the "upstream" repository: `git push -u origin master` 

These instructions are adapted from
[this webpage](http://bitdrift.com/post/4534738938/fork-your-own-project-on-github).

