# Demoblaze Katalon Automation Framework

## 📌 Overview

This project is a structured web test automation framework built using **Katalon Studio**.

The framework implements:

- Smoke Testing
- Core Regression Testing
- Data-Driven Testing (DDT)
- Reusable Test Flow Architecture
- Alert Handling Strategy
- Dynamic Element Validation
- Cart Total Verification Logic

The automation covers the e-commerce demo website:
👉 https://www.demoblaze.com

This project demonstrates real-world automation practices including modular design, reusable test components, and structured regression suites.

---

## 🛠 Tech Stack

- Katalon Studio
- Groovy (Script Mode)
- WebUI Built-in Keywords
- Internal Data-Driven Testing
- Git & GitHub

---

## 🏗 Framework Architecture
<img width="455" height="377" alt="image" src="https://github.com/user-attachments/assets/8ab246a4-c618-4133-9089-8816827f61a1" />



Additional folders:

- Object Repository
- Data Files
- Test Suites
- Profiles

---

## 🔁 Test Strategy

### 1️⃣ Smoke Suite
Validates critical user flow:
- Open Home
- Login
- Add to Cart
- Checkout

### 2️⃣ Regression Core
Covers:
- Login validation (invalid/empty)
- Cart operations
- Delete item validation
- Total update verification
- Checkout negative validation

### 3️⃣ Data-Driven Testing (DDT)
Implemented using Internal Test Data for:
- Login invalid scenarios
- Checkout invalid scenarios

This enables one test case to execute multiple data sets dynamically.

---

## 🧠 Engineering Practices Applied

- Reusable test case flow (Common folder)
- Avoidance of hardcoded test data
- Regex-based alert validation
- Async-safe validation (wait conditions)
- Element count verification using dynamic WebElements
- Clean separation between test logic and test data

---

## ▶ How to Execute

1. Open project in Katalon Studio
2. Run Test Suites:

   - `TS_Smoke`
   - `TS_Regression_Core`
   - `TS_Login_Invalid_DDT`
   - `TS_Checkout_Invalid_DDT`

---

## 📊 Key Automation Scenarios

✔ Login validation  
✔ Add to cart flow  
✔ Cart item count validation  
✔ Delete item verification  
✔ Total price recalculation  
✔ Checkout validation (negative cases)  
✔ JavaScript alert handling  

---

## 🚀 Future Enhancements

- CI/CD integration (GitHub Actions)
- Headless execution
- API automation integration
- External CSV/Excel data-driven support
- Custom Keyword abstraction

---

## 👤 Author

Sabilla Rosad  
QA Automation Engineer  
