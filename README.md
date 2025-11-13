# 1.Hysteria2在Nodejs/Python一键脚本极简部署（Pterodactyl 翼龙面板）

* 更新自适应端口，无需再手动设置

* Hysteria2版本：2.6.5 官方更新说明（原文直译）：

  修复了随着每个客户端连接而累积的服务器端内存泄漏问题

```
curl -Ls https://raw.githubusercontent.com/eishare/tuic-hy2-node.js-python/main/hy2.sh | sed 's/\r$//' | bash
```


---------------------------------------

# 2.TUIC在Nodejs/Python一键脚本极简部署（Pterodactyl 翼龙面板）

* 自适应端口，无需再手动设置

* TUIC版本：1.6.2 官方更新说明（原文直译）：

  🐛 错误修复

  （服务器）解决身份验证等待机制中的竞态条件

  ⚡ 性能

  将 chashmap 替换为 moka@Itsusinn

  🛠️ 建造

  （依赖项）将 rust-dependencies 组更新 3 次

  （依赖项）将 actions-dependencies 组更新 2 次

  ⚙️ 其他任务

  使用 cargo-zigbuild 为 amd64 linux gnu@Itsusinn

  缓存 Docker 层并更新 macOS Runner@Itsusinn

```
curl -Ls https://raw.githubusercontent.com/xiaowen-king/tuic-hy2-node.js-python/main/tuic.sh | sed 's/\r$//' | bash
```

