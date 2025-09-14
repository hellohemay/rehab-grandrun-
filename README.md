# 🏥 Rehab Grandrun Report Generator

title: Rehab Grandrun
emoji: 🏥
sdk: gradio
app_file: app.py
pinned: false

這是一個復健科 Grandrun 報告自動產生器，使用 Gradio 建立。  
只要輸入：

- 診斷 (Diagnosis)  
- PE / Functional status / Local finding  
- HTML (治療醫囑)  

👉 系統會自動產生完整的【臨床評估】【治療計畫】【出院目標】【計畫修正】。

---

## 🚀 使用方式
### 線上工具
- 填入 Diagnosis、PE、HTML。  
- 點擊按鈕 → 自動產生報告。  

### 📦 本地執行
```bash
pip install -r requirements.txt
python app.py
yaml
複製程式碼

