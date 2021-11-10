# TNEL Github
## Some important git commands and when they are used
1) This helps us tell the git commands line that we wish to add all the files
git add .<br />
2) This tells the git that we need are commited to what we just said above and git can configrue the changes to be pushed
git commit -m "title" -m "description"<br />
3) Adding the remote origin with the location on the github means we wish our code to be here in this repository
git remote add origin git@github.com:tne-lab/TNEL-Github-Tutorial.git<br />
4) where we want to merge our changes, in this or in the next branch
git branch -M sub-branch<br />
5) push the commited changes
git push -u origin sub-branch<br />