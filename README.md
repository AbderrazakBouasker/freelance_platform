# freelance_platform
to add new subdirectory :
creeate a new repo 
go to main repo

```
 
git submodule add <repo link>
git add all 
git commit -m "message"
git push

```

to refresh the subdirectories's reference 
go to main repo
 
```
git submodule update --recursive --remote
git add all
git commit -m "message"
git push

```

to clone the projet with all the submodules
 
```

git clone --recursive <project url>

```
