# 小票账本
小票自动识别记账网页，适合 iOS 夸克浏览器使用，部署在 GitHub Pages。
✅ 拍照/相册上传小票，自动OCR识别文字，自动提取金额、日期、商户
✅ 数据存在浏览器本地 IndexedDB，不上传到任何服务器
✅ 统计图表、分类记账、导出备份

## 部署步骤
1. 新建 GitHub 仓库，名字随便，推荐 `xiaopiao-book`
2. 勾选 `Add a README file`
3. 上传上面两个文件 index.html + README.md
4. 仓库 → Settings → Pages
   - Source：Deploy from a branch
   - Branch：main / root 文件夹
5. 保存，等待1~3分钟，访问地址：`https://你的用户名.github.io/xiaopiao-book/`

## 使用（iOS夸克浏览器）
直接打开上面 https 链接，不需要本地文件！
- 右下角【拍小票】，拍照或者相册选择小票照片
- 页面内自动识别小票文字（WASM OCR）
- 自动填好日期、店名、金额，核对后保存
- 账单、统计、数据导出在底部tab

> ⚠️ 重要提醒：
> 必须是 https 的 GitHub Pages 链接！
> 本地 file 文件在夸克会拦截OCR引擎，线上Pages不会拦截。