IPQ807x
git clone -b main https://github.com/VIKINGYFY/immortalwrt.git imv

ImmortalWRT
git clone -b openwrt-24.10 --single-branch https://github.com/immortalwrt/immortalwrt.git 2410

GIT PULL
 
git fetch && git reset --hard origin/master

git fetch && git reset --hard origin/main

| 命令 | 作用 |
|------|------|
| `git fetch` | 从远程仓库获取最新的提交和分支信息，不合并到本地 |
| `git reset --hard origin/main` | 将当前分支硬重置到远程 `origin/main` 的状态 |

