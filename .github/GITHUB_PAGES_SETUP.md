# 🔧 GitHub Pages 設置指導

如果網站仍然無法訪問，請按照以下步驟手動設置 GitHub Pages：

## 1️⃣ 在 GitHub Repository 中啟用 Pages

1. **進入 Repository**
   - 訪問: https://github.com/UnieAI/UnieAI-Studio-User-Guide
   - 點擊 repository 的 "Settings" 標籤

2. **設置 Pages**
   - 在左側菜單找到 "Pages" 選項
   - 點擊進入 Pages 設置頁面

3. **配置 Source**
   - Source: 選擇 "GitHub Actions"
   - 確保選擇了 main 分支

4. **保存設置**
   - 點擊 "Save" 按鈕

## 2️⃣ 檢查 GitHub Actions

1. **查看 Actions 標籤**
   - 進入 Repository 的 "Actions" 標籤
   - 查看最新的 workflow run 是否成功
   - 檢查 "Deploy to GitHub Pages" job 是否完成

## 3️⃣ 等待部署

- GitHub Pages 部署通常需要 2-5 分鐘
- 首次設置可能需要更長時間（最多 10 分鐘）

## 4️⃣ 測試網站

部署完成後，訪問：
```
https://unieai.github.io/UnieAI-Studio-User-Guide/
```

## 🔍 常見問題排查

### 如果網站仍然顯示重定向頁面：

1. **清除瀏覽器緩存**
   - 按 Ctrl+F5 刷新頁面
   - 或打開隱私/無痕瀏覽模式

2. **檢查 URL 結構**
   - 確保使用正確的 URL 格式
   - URL 應該以 `/` 結尾

3. **手動訪問 index.html**
   - 嘗試: https://unieai.github.io/UnieAI-Studio-User-Guide/index.html

## 📞 獲得幫助

如果問題持續存在：
1. 檢查 GitHub Repository 的 Settings → Pages 頁面
2. 查看 Actions 標籤中的 workflow 日誌
3. 確認 GitHub Pages 設置為 "GitHub Actions" source

網站功能應該完全正常，只是 GitHub Pages 需要手動啟用才能正常工作。