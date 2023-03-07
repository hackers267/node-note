# standard-version

`standard-version`是一个根据`git`提交历史自动生成`CHANGELOG.md`文件，并更新`package.json`中的版本号，同时给`git`打上版本号标签的应用工具库。

## 使用

```shell
standard-version --first-release # 发布首个版本，`--first-release`可以缩写为`-f`
standard-version  # 发布新的版本
standard-version --prerelease # 发布一个预发布版本 `--prerelease`可以缩写为`-p`
standard-version --release-as major # 发布一个新的主版本 `--release-as`可缩写为`-r`
standard-version --release-as minor # 发布一个新的次要版本
standard-version --prerelease alpha # 发布一个tag为alpha的预发布版本
```
