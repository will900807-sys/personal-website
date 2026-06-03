# will_station专注于AI应用落地

这是一个面向中小企业老板的个人 AI 落地专家网站，用于说明 will_station 能帮助企业把 AI 应用到获客、管理、运营、内容、数据整理和自动化流程中。

## 网站定位

- 网站名称：will_station专注于AI应用落地
- 核心定位：帮中小企业把 AI 真正用到业务里
- 目标用户：中小企业老板、园区/招商/制造/服务型企业负责人、想低成本试 AI 的团队
- 第一版形态：纯静态单页网站，适合 GitHub Pages 发布

## 本地预览

直接在浏览器中打开：

```text
index.html
```

也可以在项目目录里启动一个简单本地服务器：

```powershell
python -m http.server 8080
```

然后访问：

```text
http://localhost:8080
```

## 替换联系方式

第一版以微信作为主要联系入口。

替换微信二维码时：

1. 将微信二维码图片放到 `assets/wechat-qr.png`
2. 在 `index.html` 的联系模块中，把二维码占位区域替换为图片：

```html
<img src="assets/wechat-qr.png" alt="will_station 的微信二维码">
```

## GitHub Pages 发布

推荐使用当前仓库根目录发布：

1. 打开 GitHub 仓库 Settings
2. 找到 Pages
3. Source 选择 `Deploy from a branch`
4. Branch 选择 `main`
5. Folder 选择 `/root`
6. 保存后等待 GitHub 生成访问链接

如果私有仓库无法使用 GitHub Pages，可改为公开仓库，或使用 Vercel/Netlify 部署。

## 推广建议

- 把网站链接放到微信个人签名、朋友圈置顶和企业微信名片。
- 朋友圈和企业微信可先围绕三个主题发布内容：
  - 老板别先买 AI 工具，先找业务场景
  - 中小企业最适合先做的 5 个 AI 应用
  - 一个普通公司怎么用 AI 节省重复劳动
- 私域承接话术：
  - 你现在企业里最重复、最耗人、最难管理的一件事是什么？我可以先帮你判断适不适合用 AI。
