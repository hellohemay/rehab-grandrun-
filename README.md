# 🏥 Rehab Grandrun Report Generator

這是一個復健科 **Grandrun 報告自動產生器**，使用 [Streamlit](https://streamlit.io/) 建立。  
只要輸入：
- 診斷 (Diagnosis)
- PE / Functional status / Local finding
- HTML (治療醫囑)

👉 系統會自動產生完整的【臨床評估】【治療計畫】【出院目標】【計畫修正】。

## 🚀 使用方式
1. 打開 [線上工具](https://你的-streamlit-網址)。
2. 左側輸入 Diagnosis、PE、HTML。
3. 按下「產生報告」，右側就會顯示結果。

## 📦 本地執行
```bash
pip install -r requirements.txt
streamlit run app.py
