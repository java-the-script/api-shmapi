# Collabing on GH

- git push your files to origin master
- `git push origin master`...etc
- go on github.com, your profile/repository
- "New Pull Request"
- add comment

## the other person *Approves the Changes*
- go to organization- Pull Request tab
- see changes in tab- "Files Changed"
- approve it
- to retrieve the code from organization to your computer `git push upstream master`
- after approving changes, pull it down right away!!!!!!!!!!!!!
- then push to your own repo (origin master)!!!!!!!!!!!!!!!!

## to download
- `git pull upstream master`
- *check if you have your remotes with `git remote -v`*

## Merging conflicts
- "Can't automatically merge" ?!?! There is a conflict
- person who has a conflict does the following...
- `git pull upstream master`
- go to the conflicted file

```
/*
 <<<<<<<
your code (Current Change)
=======
existing code/other persons code (Incoming Change)
>>>>>>>>>
*/
```

- delete the markings and make any changes, add/delete whatever.
- now can do `git commit -m` again!
- 



