# 🏡 Community Event Registration Form

Link: https://event-registration-sree-sai-raghavs-projects.vercel.app/
<img width="1919" height="1014" alt="image" src="https://github.com/user-attachments/assets/4c6bcdd7-b651-4026-99e7-99df56a382fa" />

## 📋 Overview
This project is a **responsive HTML, CSS, and JavaScript form** designed for **Community Event sign‑ups**.

It includes:
- **Real‑time validation** with instant feedback
- **Custom error messages** for each field
- **Clean, user‑friendly UI**
- **Submit button enabled only when the form is valid**

---

## 🛠 Technologies Used
- **HTML5** – Semantic form structure
- **CSS3** – Styling, layout, and user feedback cues
- **Vanilla JavaScript (ES6)** – Input validation and interactivity


---

## 🚀 Features
- ✅ **Full Name validation** – Only letters and spaces, min 3 characters  
- ✅ **Email validation** – Must follow standard email format  
- ✅ **Phone validation** – Exactly 10 digits (customizable)  
- ✅ **Age restriction** – Must be ≥ 18 years old  
- ✅ **Gender selection required**  
- ✅ **Event type selection required** (Workshop, Seminar, Competition, etc.)  
- ✅ **Optional comments** – Max 300 characters with live counter  
- ✅ **Field‑specific error messages** – Displayed directly below invalid inputs  
- ✅ **Visual cues** – Green border for valid fields, red for invalid  
- ✅ **Automatic state reset** – Clears styles after successful submission  

---

## 📋 Validation Rules
| Field        | Requirement |
|--------------|-------------|
| **Full Name** | Only letters & spaces, ≥ 3 characters |
| **Email**     | Valid email format |
| **Phone**     | Exactly 10 digits |
| **Age**       | Must be 18 or older |
| **Gender**    | Must select Male or Female |
| **Event Type**| Must choose from dropdown |
| **Comments**  | Optional, max 300 characters |


---

## 🧪 Testing Suggestions
- Leave required fields empty → Should display clear error messages  
- Try invalid email (e.g., `abc@`) → Should show `"Invalid email format"`  
- Phone less/more than 10 digits → Should show `"Phone must be exactly 10 digits"`  
- Age = 17 → Should be rejected  
- Age = 18 → Passes validation  
- Comments over 300 chars → Input should stop or warning shown  

---

## 📜 License
This project is **free to use** for educational and personal purposes.

---
