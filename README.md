
## Set up new ![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white) repository and create development branch for!

1. Create a directory 'new-project'
```bash
mkdir new-project
```
2. Open a directory
```bash
cd new-project
```
3. Init defauld main branch name
```bash
git config --global init.defaultBranch "main"
```
4. Init a repo
```bash
git init .
```
5. Creacte README.md file
```bash
touch README.md
```
6. Open README.md and addv text

7. Add changes in staging area
```bash
git add .
```
8. Commit staged changes
```bash
git commit -m "init"
```
9. Let's create a "development" branch
```bash
git branch "development"
```
10. Move in created branch 
```bash
git checkout "development"
```
11. Add instructions in README.md file and commit changes 

```bash
git add . && git commit -am "added instructions"
```
12. Move in "main" branch and merge "development" into "main" branch

```bash
git checkout main
git merge development
```
13. Check RREADME.md file and commit

```bash
git add . && git commit -am "merged development"
```