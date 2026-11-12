# 最后一跃 · 节奏共创实验室

一个不需要构建步骤的静态 HTML 课堂应用。

## 本地检查

在此目录运行：

```bash
python3 -m http.server 8000
```

然后访问 http://localhost:8000 。

## Vercel 发布

推荐打开 https://vercel.com/new ，使用 GitHub 导入包含本目录文件的仓库：
- Framework Preset: Other
- Build Command: 留空
- Output Directory: 留空（仓库根目录就是项目）
- 部署后打开生成的 `.vercel.app` 链接

也可以安装 Vercel CLI 后在项目目录执行 `npx vercel --prod`，按提示登录和部署。

## 注意

节奏训练器生成的是课程教学节拍与分组示范，并非对原音频自动转写。原曲播放器和训练器不保证精确同步。浏览器一般需要用户点击“开始训练”后才允许合成打击音播放。
