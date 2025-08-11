# 🎓 Inter College Competition Registration Form

## 📋 Overview
This project is a **responsive HTML, CSS, and JavaScript form** for registering participants in an **Inter College Competition**.

It includes:
- **Real-time input validation** (name, email, phone, age, gender, event type)
- **Custom error messages** and visual feedback
- **Character counter** for optional comments
- **Submit button enabled only when all inputs are valid**

The form is styled with a **solid blue background**, and the registration card is centered for a clean, accessible UI.

---

## 🛠 Technologies Used
- **HTML5** – Structure
- **CSS3** – Styles, colors, layouts
- **Vanilla JavaScript (ES6)** – Validation & interactivity

---


---

## 🚀 Features
- ✅ **Full Name validation** – Only letters and spaces, min 3 characters  
- ✅ **Email validation** – Must match standard format  
- ✅ **Phone validation** – Exactly 10 digits  
- ✅ **Age restriction** – ≥ 18 years old  
- ✅ **Gender selection required**  
- ✅ **Event type selection required**  
- ✅ **Optional comments** – Max 300 chars with live counter  
- ✅ **Error messages** – Specific, shown under each invalid field  
- ✅ **Visual feedback** – Green border for valid, red for invalid  
- ✅ **Success reset** – Clears after successful submission  

---

## 📋 Validation Rules
| Field        | Requirement |
|--------------|-------------|
| **Full Name** | Letters & spaces only, ≥ 3 chars |
| **Email**     | Valid email format |
| **Phone**     | 10 digits only |
| **Age**       | Must be ≥ 18 |
| **Gender**    | Mandatory |
| **Event Type**| Mandatory |
| **Comments**  | Optional; ≤ 300 chars |


---

## 🧪 Testing Suggestions
- Leave fields blank → Errors shown, button disabled  
- Wrong email format → Error message instantly  
- Phone < 10 digits → Error message instantly  
- Age = 17 → Fail  
- Age = 18 → Pass  
- Comments > 300 chars → Counter stops at 300  

---

## 📜 License
This project is **free to use** for education and personal purposes.

---

