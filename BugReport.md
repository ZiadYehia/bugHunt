# 🐞 UI Bug Report: Arabic Table Misalignment (Web Only)

### 🆔 Test Charter ID: `UI-AR-TBL-001`
**🧑‍💻 Reporter**: Ziad Yehia  
**📅 Date Submitted**: 16 April 2025  
**🎯 Assigned to**: QA Head – Eng. Tarek Roshdy  
**⚠️ Severity**: Medium  
**🔻 Priority**: Low  

---

## 🔎 Summary
A layout issue occurs when displaying comparison tables in **Arabic** on **desktop browsers**. The table becomes **misaligned**, reducing readability and harming UX for Arabic-speaking users. The bug is **not present in English** or in **mobile apps**.

---

## 🌐 Affected URL
[https://chatgpt.com](https://chatgpt.com)

---

<details>
<summary><strong>📷 Screenshots / Videos (Click to Expand)</strong></summary>

- Google Drive: [View Folder](https://drive.google.com/drive/folders/1b1MAKRKlSrFOk9RSvC-GgeVP_hxRErMO?usp=sharing)

</details>

---

## 🧪 Test Environment

| Device / OS            | Browser / App           | Status |
|------------------------|-------------------------|--------|
| Windows 11             | Chrome 135.0.7049.96    | ❌ Affected |
| Windows 11             | Edge 135.0.1379.73      | ❌ Affected |
| iPhone 13 Pro Max      | ChatGPT App             | ✅ Not Affected |
| Samsung Note 10 Plus   | ChatGPT App             | ✅ Not Affected |

---

## 📋 Steps to Reproduce

1. Visit [https://chatgpt.com](https://chatgpt.com) using a desktop browser.
2. Change interface language to Arabic.
3. Ask for a comparison table in Arabic (e.g. `...أعطني جدول مقارنة بين`).
4. Observe the misalignment of the table.

---

## ✅ Expected Behavior

- Table should be **well-aligned** regardless of language.
- Layout should **adapt to screen size**.
- Readability should be **consistent** across devices and languages.

---

## ❌ Actual Behavior

- Table becomes **misaligned** when Arabic is selected on desktop browsers.
- **More severe** on narrower screens.
- English layout and mobile apps are not affected.

---

## 📬 Contact Info

- 📧 Reporter: [ziad.m.yehia@gmail.com](mailto:ziad.m.yehia@gmail.com)  
- 📧 QA Head: [tarekroshdy@outlook.com](mailto:tarekroshdy@outlook.com)
