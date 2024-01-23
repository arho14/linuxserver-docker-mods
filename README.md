# Emby CustomCssJs 插件 Docker Mod

这个模块将[CustomCssJs](https://github.com/Shurelol/Emby.CustomCssJS)插件安装到 Linuxserver.io 的 emby 中。插件具体使用方法请看作者仓库：[Shurelol/Emby.CustomCssJs](https://github.com/Shurelol/Emby.CustomCssJS)

## 使用方法

在 Emby docker 参数中加入环境变量`DOCKER_MODS=arho14/emby-custom-css-js`,多个模块使用`|`隔开，例如：`DOCKER_MODS=arho14/emby-custom-css-js|linuxserver/mods:emby-second-mod`
