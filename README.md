# 求职作品集网站（自包含 · 可直接部署）

## 页面

| 文件 | 内容 |
|---|---|
| `index.html` | 主页：关于我 · 两个案例入口 · 真实数据研究 |
| `catnips-case.html` | 案例 02：Catnip.AI × 北美市场 0→1 运营方案 |
| `watrix-worldline.html` | 案例 03：Watrix Worldline 海外冷启动方案 |
| `assets/` | 两张真实数据图表 |

## 部署

无外部依赖（无 CDN / 网络字体 / 前端框架），任意静态托管直接把本目录传上去即可：

- **GitHub Pages**：新建仓库 → 上传本目录文件 → Settings → Pages → Source 选 main 分支根目录
- **Netlify**：把本目录拖进 netlify.com/drop
- **Vercel**：Import 仓库后直接部署

## 发布前检查

- 联系方式：页面底部为「联系方式见简历」，如需替换为邮箱/链接，在三个 HTML 中搜索 `联系方式见简历` 修改
- 竞品数据：采集于 2026-11，正式投递前建议按各页面「数据来源」节列出的链接复核一遍
- 示例数据：案例页中标注 `EXAMPLE` 的数字为演示用，起号后替换为真实数据
