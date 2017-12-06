# git_basic_command
> a document about git basic command

* help command
```
git help
```
* clone origin store
```
git clone store_address
```
* check status
```
git status
```
* check modification
```
git diff
```
* print current version information
```
git log
```
* establish branch
```
git branch new_name
```
* switch branch
```
git checkout
```
* add new file
```
git add .    <"." on behalf of all>
```
* commit file
```
git commit -m"message"    <message defined by yourself>
```
* push origin branch
```
git push origin branch_name
```
* pull origin branch
```
git pull origin branch_name
```
* merge branch
```
git merge branch_name
```
* rename local branch **rename origin branch：rename local branch->delete origin branch->push to origin**
```
git branch -m old_name new_name
```
* delete local branch
```
git branch -D branch_name
```
* delete origin branch
```
git push origin --delete branch_name
```
* version roolback pre/previous N version
```
git reset --hard HEAD^
git reset --hard HEAD~N
```
* 版本回退 回退到指定ID版本
```
git reset --hard commit_id
```
* 查看版本ID <用于错误回滚流程后的复原`git reset --hard commit_id`>
```
git reflog
```
> whole process
```
mkdir folders
git clone origin_address
cd folders
npm install
npm run dev <the configuration file works>
<open a new window>
git checkout -b develop
(git pull origin develop)
git checkout -b feature/xxx/xxx
git add .
git commit -m"xxx"
git push origin feature/xxx/xxx
git checkout develop
git pull origin develop
git merge feature/xxx/xxx <resolve the conflict>
```
### [Jump to Chinese documents](https://github.com/ajun568/git_basic_command/wiki)
