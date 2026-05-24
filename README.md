# 🚀 DMoney Performance Testing using JMeter

![JMeter](https://img.shields.io/badge/Apache-JMeter-D22128?style=for-the-badge&logo=apache)
![Performance Testing](https://img.shields.io/badge/Performance-Testing-blue?style=for-the-badge)
![CSV Data Driven](https://img.shields.io/badge/CSV-Data%20Driven-success?style=for-the-badge)
![Newman](https://img.shields.io/badge/API-Tested-orange?style=for-the-badge)
![GitHub](https://img.shields.io/badge/GitHub-Repository-black?style=for-the-badge&logo=github)

---

# 📌 Project Overview

This project demonstrates a complete **Performance Testing workflow** using **Apache JMeter** for the **DMoney financial transaction system**.

The objective of this assignment was to simulate multiple real-world transaction scenarios with concurrent users and validate system performance under load.

The project includes:

✅ Multi-threaded transaction execution  
✅ CSV data-driven testing  
✅ Dynamic random transaction amounts  
✅ Token reuse strategy  
✅ Deposit, Send Money & Payment simulation  
✅ Assertions for transaction validation  
✅ Performance test execution using JMeter  

---

# 🎯 Assignment Scenario

The following scenarios were implemented successfully:

### 🔹 Deposit Scenario
- 5 Agents perform deposits for 10 Customers

### 🔹 Send Money Scenario
- 5 Customers send money to another 10 Customers

### 🔹 Payment Scenario
- 5 Customers make payments to 2 Merchants

---

# 🛠️ Tools & Technologies Used

| Tool | Purpose |
|------|----------|
| Apache JMeter | Performance Testing |
| CSV Data Set Config | Data-driven testing |
| Random Variable Controller | Dynamic amount generation |
| VS Code | Script & File Management |
| Git & GitHub | Version Control |
| DMoney API | Transaction System |

---

# 📂 Project Structure

```bash
DMoney-JMeter-Performance-Testing/
│
├── deposit.csv
├── sendMoney.csv
├── payment.csv
├── dmoney.jmx
├── README.md
├── .gitignore
└── Reports/
```

---

# 🔄 Performance Testing Workflow

## ✅ Deposit Thread Group

- Agent logs in
- Token generated & reused
- Dynamic deposit transactions executed
- Multiple customer accounts tested

---

## ✅ Send Money Thread Group

- Customer logs in
- Send money transactions performed
- Multiple receivers tested
- Assertions added for validation

---

## ✅ Payment Thread Group

- Customer payment simulation
- Merchant account testing
- Random amount generation
- Concurrent user execution

---

# ⚙️ JMeter Configuration

| Configuration | Value |
|---|---|
| Thread Groups | 3 |
| Ramp-up Time | 120 Seconds |
| CSV Files Used | 3 |
| Dynamic Random Amount | Enabled |
| Assertions Added | Yes |
| Token Reuse | Yes |

---

# 🧪 Assertions Used

The following assertions were added to validate successful transactions:

- Status code validation
- Response message validation
- Transaction success verification
- Response data checking
- API response time validation

---

# 📁 CSV Files Used

## 📌 Deposit CSV

```csv
agentPhone,customerPhone
```

---

## 📌 Send Money CSV

```csv
senderPhone,receiverPhone
```

---

## 📌 Payment CSV

```csv
customerPhone,merchantPhone
```

---

# 🎲 Dynamic Transaction Amount

Random Variable Controller was used to generate dynamic transaction amounts during test execution.

This prevents:

- Balance exhaustion
- Duplicate transactions
- Fixed amount dependency

---

# 🚀 How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone YOUR_GITHUB_REPOSITORY_LINK
```

---

## 2️⃣ Open JMeter

Launch Apache JMeter.

---

## 3️⃣ Open Project File

Open:

```bash
dmoney.jmx
```

---

## 4️⃣ Configure CSV Files

Ensure these files are correctly linked:

- deposit.csv
- sendMoney.csv
- payment.csv

---

## 5️⃣ Run Performance Test

Click:

```bash
Start ▶
```

from Apache JMeter.

---

# 📊 Test Scenarios Summary

| Scenario | Users | Target |
|---|---|---|
| Deposit | 5 Agents | 10 Customers |
| Send Money | 5 Customers | 10 Customers |
| Payment | 5 Customers | 2 Merchants |

---

# 🔥 Key Features Implemented

| Feature | Status |
|---|---|
| Multi-threading | ✅ |
| CSV Data Driven Testing | ✅ |
| Dynamic Random Amount | ✅ |
| Token Reuse | ✅ |
| Assertions | ✅ |
| Concurrent Transactions | ✅ |
| Performance Simulation | ✅ |

---

# 📈 Performance Testing Goals

The testing aimed to verify:

- System stability under concurrent load
- Transaction success rate
- API responsiveness
- Data handling capability
- Real-world transaction simulation

---

# 🧠 Learning Outcomes

This project helped practice:

- Apache JMeter fundamentals
- Performance testing concepts
- Thread Group management
- CSV Data Set Config usage
- Random Variable Controller
- API load simulation
- Assertion handling
- Concurrent transaction testing

---

# 👨‍💻 Author Information

| Info | Details |
|---|---|
| Name | Fahad Bin Hossain |
| Batch | 18 |
| Project | DMoney Performance Testing using JMeter |

---

# ✅ Assignment Status

✔️ Performance Testing Completed  
✔️ Multi-thread Scenarios Implemented  
✔️ Assertions Added Successfully  
✔️ CSV Data Driven Testing Completed  
✔️ Dynamic Transactions Implemented  
✔️ Project Ready for Submission  

---

# 🙌 Conclusion

This project successfully demonstrates a complete real-world performance testing workflow using Apache JMeter for a financial transaction system. Multiple transaction scenarios were simulated concurrently using dynamic test data, token reuse strategies, and assertions to validate successful execution.

The implementation reflects practical performance testing techniques used in real-world API testing environments.

---
