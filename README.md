# freelance_platform
to add new subdirectory :
creeate a new repo 
go to main repo

```bash
 
git submodule add <repo link>
git add all 
git commit -m "message"
git push

```

to refresh the subdirectories's reference 
go to main repo
 
```bash
git submodule update --recursive --remote
git add all
git commit -m "message"
git push

```

to clone the projet with all the submodules
 
```bashgit submodule update --init --recursive

git clone --recursive <project url>

```
