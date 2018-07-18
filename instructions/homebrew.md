# Homebrew

Mac 软件包管理器

- homepage

  <https://brew.sh/index_zh-cn>

- 安装 Homebrew

运行命令：

```shell
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

- brew 常用命令

| 命令                           |                            |
| ------------------------------ | -------------------------- |
| `brew -v`                      | 查看 Homebrew 版本         |
| `brew update`                  | 更新 Homebrew 自身         |
| `brew list`                    | 查看已安装的软件           |
| `brew search [packageName]`    | 搜索软件                   |
| `brew install [packageName]`   | 安装具体的软件             |
| `brew uninstall [packageName]` | 卸载具体的软件             |
| `brew outdated`                | 查看已安装的软件是否有更新 |
| `brew upgrade`                 | 更新所有已安装的软件       |
| `brew upgrade [packageName]`   | 更新具体软件               |
