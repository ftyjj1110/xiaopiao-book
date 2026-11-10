购物小票管家 V2 测试版

使用方法：
1. 将 index.html 上传到 GitHub 仓库根目录。
2. 在仓库 Settings -> Pages 中启用 GitHub Pages，选择 Deploy from a branch、main、/(root) 并保存。
3. 等待部署完成后，用 Pages 提供的网址打开。
4. 首次 OCR 需要联网加载 Tesseract.js 和中文/英文识别语言数据。
5. 识别结果需要人工核对。数据保存在当前浏览器的 IndexedDB 中，请定期导出 JSON 备份。

注意：此版本为测试版；请先用不重要的小票试用。不要清除浏览器网站数据，否则本地记录可能丢失。
