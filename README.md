# 蔚蓝档案记忆大厅测试原型

用于中文 Miraheze Wiki 的三个 Spine 4.2.33 实例：CH0069、CH0145、Nagisa。

测试范围：摄像机自适配、摸头/视线/说话动作、缩放和平移。不发布或加载语音。

自创播放器仅发布经过混淆的构建产物，不提供源码映射；混淆不保证浏览器代码无法还原。可读源码和构建工具保留于维护者本地。

游戏素材权利归 NEXON Games、Yostar 及相关权利人所有，不适用维基正文的 CC BY-SA 许可。第三方 Spine Runtime 遵循 `vendor/SPINE-LICENSE.txt`。本仓库不授予额外的素材或运行时授权。

原始实例文件通过 `asset-manifest.json` 记录 SHA-256。Spine Runtime 的唯一包装调整是使用独立 `BASpineRuntime` 命名空间，以避免覆盖站点全局变量。

运行：在此目录启动 HTTP 静态服务器，访问 `index.html`。维基采用固定 Git commit 的 jsDelivr 地址加载构建产物和资源。
