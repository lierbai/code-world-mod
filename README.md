# Code World Mod

License = CC0 license.
## Setup

有关安装说明，请参阅 [fabric wiki page](https://fabricmc.net/wiki/tutorial:setup) 使用的IDE不同操作也不同.

```
 if [ IDE ='VS CODE' && os='windows10 20H2' ];then
    > ./gradlew vscode          # 生成运行配置
    > ./gradlew genSources      # 生成源
    > 打开 build.gradle 按下 Shift + Alt + U 来刷新Java项目
    # 故障排除
    > ./gradlew cleanloom       # 来刷新缓存
    > ./gradlew downloadAssets  # 故障排除_缺少声音
 fi
```
