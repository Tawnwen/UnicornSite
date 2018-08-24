# UnicornSite
Testing out GitHub Pages


Directions to replace master branch with gh-pages branch:

ON GITHUB:
1) Create gh-pages as new branch.
2) Go to settings -> branches and change default branch to gh-pages (ignore unintended consequences)
3) Delete the old master branch

USING GIT:
1) Delete your local master branch by doing:
  - git branch <placeholder>  # make new placeholder branch
  - git checkout <placeholder>  # checkout to new branch
  - git branch -D master  # delete local master branch
2) Delete your remote master branch. You cannot delete from terminal since that is the default Github branch.
  - git push origin placeholder # push placeholder branch to github
3) Go on GitHub and manually change the default branch as described above
4) Delete the remote master branch using:
  - git push origin :master
