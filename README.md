#  從世界到台灣：量子運算入門實作

歡迎！這裡是課程的實作教材。今天你會親手寫出一支量子程式，做出量子世界最神奇的現象之一：**糾纏**。

>  **請用筆電開啟下面的連結。** Colab 在手機上很難操作，手機上看這頁說明就好。

##  課堂實作（模擬器）

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_ID/quantum-intro-course/blob/main/01_hello_quantum.ipynb)

- **開啟後第一件事**：點選「檔案 → 在雲端硬碟中儲存副本」，你的修改才會被保存
- **內容**：疊加與糾纏、Bell 態電路、shots 的意義、雜訊模擬、挑戰題

## 回家作業（真實量子電腦）

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_ID/quantum-intro-course/blob/main/02_homework_real_qpu.ipynb)

- **需要準備**：免費的 [IBM Quantum Platform](https://quantum.cloud.ibm.com/) 帳號（選擇 Open Plan）
- **內容**：把課堂上的電路送到 IBM 的真實量子電腦執行，和模擬器結果比較


> 🔐 **IBM API key 就像密碼**：不要貼在程式碼裡、不要截圖、不要分享給別人。作業筆記本會用隱藏輸入框請你輸入。

## 常見問題

**安裝那一格跑完，下一格出現錯誤？**
點選「執行階段 → 重新啟動工作階段」，再從第一格開始依序執行。

**真機一直在排隊？**
這是正常的，許多人共用同一台機器。記下工作編號，晚點再用作業筆記本中的方法取回結果，或到 [Workloads 頁面](https://quantum.cloud.ibm.com/workloads)查看狀態。

**圖表的文字為什麼是英文？**
Colab 預設的繪圖字型不支援中文，為了避免出現亂碼方塊，圖表標籤都使用英文。

## 📚 延伸學習

- [IBM Quantum Learning](https://quantum.cloud.ibm.com/learning/en)：IBM 官方免費量子課程
- [Qiskit 文件](https://quantum.cloud.ibm.com/docs/en/guides)：量子程式套件的完整說明
- [IBM Quantum Composer](https://quantum.cloud.ibm.com/composer)：用拖拉的方式組量子電路
- [研之有物：量子電腦的關鍵，中研院自製量子位元大揭密](https://research.sinica.edu.tw/superconducting-quantum-bit-technology-chung-ting-ke/)：認識台灣自製的超導量子電腦

## 🙏 出處

本教材改寫自 IBM Quantum Learning 課程〈[Build and run your first quantum program](https://quantum.cloud.ibm.com/learning/en/courses/use-a-qc-today/build-and-run-your-first-quantum-program)〉，並加入中文說明、課堂小實驗與挑戰題。
