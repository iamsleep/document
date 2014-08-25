document
========

* git repository remote control
  * step 1 : git remote add "local name" "git path"
  * step 2 : git remote -v 顯示已經加入的 git path
  * step 3 : git branch --track "branch name" "git path"
  * step 4 : pull / push repository directly.
* 如果 remote 的 repository 的 link remove，當有改動的時候，會 show message -> git push --set-upstream origin "your branch"，會把 branch mv 到 origin 中
