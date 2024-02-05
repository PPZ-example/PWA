# PWA examples
PWA (Progressive Web App)，比 WA (Web App，就是普通网页) 多了一个 P。

## 最简 PWA
最简单的  只是在普通网页（Web App）的基础上，在 `<head>` 标签里添加一个标签，这个标签要加载一个配置文件（就像我们使用 `<link>` 标签来加载 css 文件一样），……
+ [源码](../PWA/simple)
+ [线上效果]()

## 纯静态网站缓存策略
如果你的网站：
+ 是静态的（没有后端服务（java, go, php, nodejs...），没有数据库）
+ 所有静态资源（html, js, css）只有**全量更新**
+ 启动时，优先使用旧版本（如果有）；只在检测到有新版本时，询问用户是否需要更新，并且在用户的允许后加载新版本

那么，这个案例的缓存策略可做参考。

> 新版本加载失败时，要不要恢复旧版本？
> 目前来看，有一定的开发和测试成本，得不偿失。

+ 源码：todo
+ 线上效果：todo
