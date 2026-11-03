# 顺德周末旅行手册

这是一个零外部依赖的单文件旅行手册。公开网页只需 `index.html`，不含订单号、证件号、房间号或支付信息。

## Cloudflare Pages 自动发布（免费方案）

1. 登录 Cloudflare，在 **Workers & Pages → Create application → Pages → Connect to Git** 连接此 GitHub 仓库 `JOJ008/SD-11.6`。
2. 授权 Cloudflare 访问该仓库。
3. Framework preset 选择 **None**；Build command 留空；Build output directory 填 `/`（若界面不接受 `/`，填 `.`）。
4. 开始部署。成功后 Cloudflare 会给出 `https://<项目名>.pages.dev` 公开网址。
5. 之后推送到 `main` 分支会自动重新部署。修改旅行内容只需编辑 `index.html` 并提交推送。

**需在电脑完成：**Cloudflare 登录/授权、首次连接 GitHub、检查首次部署网址。日常改页面也可以在 GitHub 网页端完成，但最好用电脑预览。

当前路线和车程为规划估算；未核实的停车费、店铺分店/营业时间没有编造。Google 地图链接需联网；页面其余内容可离线打开。
