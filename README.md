# 🐞 UI Bug Report: Arabic Table Misalignment (Web Only)

> A real-world bug discovered during manual UI testing of ChatGPT’s Arabic interface on web browsers.

---

### 📌 Metadata

| Key               | Value                               |
|------------------|-------------------------------------|
| **Test Charter ID** | `UI-AR-TBL-001`                      |
| **Reporter**      | Ziad Yehia                          |
| **Date Submitted**| 16 April 2025                       |
| **Assigned To**   | QA Head – Eng. Tarek Roshdy         |
| **Severity**      | ⚠️ Medium                            |
| **Priority**      | 🔻 Low                               |

---

## 🔍 Summary

A **UI misalignment** occurs when rendering **comparison tables in Arabic** on **desktop browsers**, significantly impacting layout and readability for Arabic-speaking users.

> This issue does **not** appear:
> - In the English version.
> - On the **ChatGPT mobile apps**.

---

## 🌐 Affected Platform

- **Website**: [chatgpt.com](https://chatgpt.com)

---

<details>
<summary><strong>📸 Screenshots / Video Evidence</strong></summary>

🗂️ [Google Drive Folder](https://drive.google.com/drive/folders/1b1MAKRKlSrFOk9RSvC-GgeVP_hxRErMO?usp=sharing)  
Includes screenshots and screen recordings demonstrating the issue.

</details>

---

## 🧪 Test Environment Matrix

| Device               | Platform / Browser            | Affected?     |
|----------------------|-------------------------------|---------------|
| 💻 Windows 11        | Chrome 135.0.7049.96          | ❌ Yes         |
| 💻 Windows 11        | Edge 135.0.1379.73            | ❌ Yes         |
| 📱 iPhone 13 Pro Max | ChatGPT App                   | ✅ No          |
| 📱 Samsung Note 10+  | ChatGPT App                   | ✅ No          |

---

## 🧭 Steps to Reproduce

1. Open [chatgpt.com](https://chatgpt.com) on any **desktop browser**.
2. Change the interface language to **Arabic**.
3. Prompt ChatGPT with a request for a **comparison table** in Arabic (e.g., `أعطني جدول مقارنة بين...`).
4. Observe the rendered table → it appears **misaligned** and inconsistent.

---

## ✅ Expected Result

- Table headers and rows are properly **aligned**.
- Responsive layout across all screen sizes.
- Visually consistent and readable in **all languages**.

---

## ❌ Actual Result

- Table becomes **visually misaligned** in Arabic on desktop.
- Misalignment becomes **worse on narrow screens**.
- Mobile app rendering is unaffected.

---

## 📬 Contact

- 📧 Reporter: [ziad.m.yehia@gmail.com](mailto:ziad.m.yehia@gmail.com)  
- 📧 QA Head: [tarekroshdy@outlook.com](mailto:tarekroshdy@outlook.com)

---

> 🧠 **Note:** This bug highlights the importance of multilingual UI testing and cross-platform consistency.  
> A fix will improve accessibility and usability for right-to-left (RTL) language users on desktop.
