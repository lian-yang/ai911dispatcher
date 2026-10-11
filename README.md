# ai911dispatcher.com — AI 911 Dispatcher 资讯站

主词 **ai 911 dispatcher**（KGR 0.036，110/月，趋势 up）+ 内容矩阵 salary/jobs/certification（哥飞版 KD 8.7-16.9 全极易）。

## 文件

- `index.html` — 主词页 + 交互式 triage 分类 demo（首屏即功能，拉停留时长）
- `salary.html` / `jobs.html` / `certification.html` / `will-ai-replace-dispatchers.html` — 内页矩阵
- `sitemap.xml` / `robots.txt`
- 全站静态 HTML，零依赖，Vercel 直接部署

## 上站清单（哥飞 15 条对照）

| # | 事项 | 状态 |
|---|---|---|
| 1 | 词是否新词 | ✅ Trends 上升期（ai 911 dispatcher） |
| 2 | 搜索量估算 | ✅ 110/月（ideas 接口实测） |
| 3-4 | 域名 | ⬜ **用户注册 ai911dispatcher.com**（Namecheap/Porkbun） |
| 5 | 全站内容解释词 | ✅ 5 页互相内链 |
| 6 | 在线体验功能 | ✅ triage demo |
| 7 | 内页覆盖 | ✅ 4 内页 + 主页 |
| 8 | 内链 | ✅ 全站互链 |
| 9 | 多语言 | ⬜ 上线后按流量加子目录版本 |
| 10 | GSC 提交 | ⬜ 部署后（需要用户 Google 账号） |
| 11 | Bing/Yandex 提交 | ⬜ 部署后 |
| 12 | 外链 10 条/天 | ⬜ 上线后（可配合 web.cafe 悬赏的外链渠道清单） |
| 13-14 | GA4 | ⬜ 部署后插入 measurement ID |
| 15 | UV>500 再申 Adsense | ⬜ 后置 |

## 部署（方案A：Cloudflare + Vercel）

1. 注册商买域名 → DNS 改 Cloudflare（复制两个 nameserver）
2. GitHub 建 Public 仓库，推本目录
3. Vercel Import → Deploy → Domains 绑定自定义域名
4. Cloudflare 加 CNAME（www/根域）+ A 记录，SSL 设"完全（严格）"防重定向循环
5. 部署后：GSC/Bing 提交 sitemap、加 GA4

## 备注

- 页面内 salary 等数字为编辑性估算，措辞已做 hedge；上线前可再核一轮公开数据
- canonical/TDK 按 ai911dispatcher.com 写好，若换域名需全站替换
