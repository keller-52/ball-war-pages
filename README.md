# BALL WAR · 小球战争

[打开游戏](https://keller-52.github.io/ball-war-pages/)

当前发布版本为 **v0.10.0 · 余光群岛与人物绘卷**。首页可以进入自动对战，或在「弹射对战」中玩单机人机、同屏双人和教程关卡。公网好友房暂缓上线。

本仓库保存游戏的静态构建产物，由 GitHub Pages 从 `main` 分支根目录发布。

维护者在源码仓库运行 `npm ci` 和 `npm run build`，再把 `dist/` 中的构建产物同步到这里，保留 `.nojekyll` 和这份发布说明。`room-config.json` 中的 `roomApiUrl` 当前为 `null`。
