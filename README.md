# Meet妙记产品素材库

本仓库为 Meet妙记（Mionote）的公开产品素材库，供 AgentX、内容生成 Skill 和各平台发布工具读取。

## 链接使用规则

- AgentX 阅读、人工预览：使用 `https://github.com/MeetMiaoji/mionote-assets/blob/main/<路径>`。
- MCP、发布脚本下载或上传图片：使用 `https://raw.githubusercontent.com/MeetMiaoji/mionote-assets/main/<路径>`。
- 不要把 `/blob/` 链接交给要求“图片直链”的上传工具，因为它返回的是 HTML 页面。
- 原始素材只作为候选库；每篇稿件仍须在审核包中明确列出选中图片、用途、顺序和插入位置。

## 目录

| 类别 | 路径 | 用途 |
| --- | --- | --- |
| Logo | `mionote_logo.png` | 品牌标识 |
| 宣传图 | `promotional/` | 小红书/即刻配图、文章内插图 |
| 产品截图 | `screenshots/` | 功能说明、教程、评测和回答配图 |

完整的机器可读清单见 [`assets.json`](./assets.json)。

## 选图建议

- 小红书：必须选用不含二维码、网址或其他站外引流元素的图片；标题、正文和话题同样不得包含外链。
- 即刻：图片与官网链接二选一；选择图片时优先使用生活化、信息密度适中的宣传图。
- 知乎：使用产品截图支撑具体步骤或功能，不把图片当作结论证据。
- 少数派：正文截图放在对应功能段落之后；如需封面，另行选择或制作不含风险元素且符合平台比例的图片。
