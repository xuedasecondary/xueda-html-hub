# 学达 HTML 教学资源中心

第一版 HTML Hub，适合使用 VS Code 编辑，并可发布到 GitHub Pages。

## 本地开启

1. 用 VS Code 打开整个 `xueda-html-hub` 文件夹。
2. 安装 VS Code 扩充功能 `Live Server`。
3. 右键 `index.html`，选择 `Open with Live Server`。

## 第一版功能

- 六个科目：BMP、BMK、BI、SEJ、MM、SC
- 建立、改名和删除文件夹
- 粘贴、储存、编辑、运行和删除完整 HTML
- 搜索及电脑/手机自适应
- 使用浏览器 localStorage 保存资料

## 重要限制

资料只存在当前浏览器。清除浏览器资料或换电脑后不会同步。第二版才连接 Firebase Authentication 与 Cloud Firestore。

不要储存密码、API Key 或不信任的 HTML。

## GitHub Pages

上传这些文件到公开 GitHub repository，然后进入 `Settings → Pages → Deploy from a branch → main / root → Save`。
