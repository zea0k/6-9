# 微型轉型研究成果網站

## 📁 檔案結構

```
research-site/
├── index.html
└── assets/
    ├── members/
    │   ├── member1.jpg   ← 謝佳和
    │   ├── member2.jpg   ← 李暐
    │   ├── member3.jpg   ← 卓翔賀
    │   └── member4.jpg   ← 蔡宇晉
    └── files/
        ├── report.pdf      ← 研究報告
        ├── slides.pdf      ← 10 頁簡報 (請自行加入)
        ├── podcast.m4a     ← Podcast 音檔
        ├── transcript.docx ← Podcast 逐字稿
        └── video.mp4       ← Video Overview
```

## 🚀 上傳到 GitHub Pages 步驟

1. 到 https://github.com 建立一個新的 Repository，例如命名 `micro-transformation`。
2. 把本資料夾內的 **所有檔案 (含 assets 資料夾)** 上傳到 repo 根目錄。
   - 網頁上 `Add file → Upload files` 或用 Git CLI：
     ```bash
     git init
     git add .
     git commit -m "init"
     git branch -M main
     git remote add origin https://github.com/<你的帳號>/<repo>.git
     git push -u origin main
     ```
3. 進入該 Repo 的 `Settings → Pages`。
4. 在 **Source** 選 `Deploy from a branch`，Branch 選 `main` / `/ (root)`，按 Save。
5. 等 1～2 分鐘，網址會出現在 Pages 頁面：
   `https://<你的帳號>.github.io/<repo>/`

## ⚠️ 注意事項
- 因 GitHub 單檔上限 100MB，若 `video.mp4` 過大，建議改上傳到 YouTube 後用 `<iframe>` 嵌入。
- 檔名請保持英文 (已幫你重新命名)，避免中文編碼問題。
- 若要替換簡報，請將 PPT 另存為 PDF 並命名 `slides.pdf` 放入 `assets/files/`。
