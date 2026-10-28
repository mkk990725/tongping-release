# 同屏字幕 · iOS 发布仓库

本仓库只存放**未签名 IPA 安装包**与 SideStore 源清单（`source.json`），供 iPhone 上的 [SideStore](https://sidestore.io) 安装与更新「同屏字幕」。源代码不在本仓库。

## 添加源（手机上安装）

1. iPhone 上安装 SideStore（官网 sidestore.io，安装本体仅需电脑协助一次）
2. SideStore → Sources → 右上角 **+** → 粘贴下面的地址 → Add Source
3. 在源里找到「同屏字幕」→ Install

```
https://github.com/mkk990725/tongping-release/releases/latest/download/source.json
```

## 更新 App

发布新版本后，SideStore 的 Apps 页会显示可用更新，直接**覆盖安装**即可。不要删除后重装——会丢失 App 内保存的服务地址等数据。

## 须知（诚实声明）

- 本 IPA **未签名**：安装时由 SideStore 用你自己的 Apple ID 现场签名，不含任何预置凭据
- 免费 Apple ID 证书**七天有效**：需要定期打开 SideStore 让它续签（建议每周一次；iOS 不保证后台任务按时执行）
- 免费账号同一证书下最多 3 个活跃 App，装满需要先停用其他侧载 App
- SideStore 是第三方开源（AGPL-3.0）工具，与本项目无隶属关系
- App 运行需要自备「同屏字幕」服务端（HTTPS 地址 + 安装码激活）；服务端软件与源码均不在本仓库分发

## 版本

当前发布：**0.2.4（build 7）**，见 [Releases](https://github.com/mkk990725/tongping-release/releases)。
