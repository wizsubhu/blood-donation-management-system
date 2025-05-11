# 🩸 Blood Donation Management System (BDMS) – SQL Project

A comprehensive database-driven project designed to manage and streamline the operations of a blood donation ecosystem. It supports donor and patient tracking, blood bank inventory, and donation records using well-structured relational databases with ER diagrams, normalization, and SQL procedures.

---

## 📌 Project Highlights

- 🗂️ Structured relational database with **4 core tables**
- 🧠 Designed E-R Diagram with entities: Donor, Patient, Blood Bank, Donation
- 💾 CRUD operations implemented (Insert, Update, Delete)
- ⚙️ Stored **Procedures**, **Functions**, and **Triggers** for automated behavior
- ✅ Normalized up to **3NF** for optimal schema efficiency
- 📋 Output screenshots of SQL execution results

---

## 🗃️ Tables Designed

1. **Patient**  
   Fields: ID, Name, Blood Group, Disease, Address, Contact No.

2. **Donor**  
   Fields: ID, Name, Blood Group, Disease, Address, Contact No.

3. **Blood Bank**  
   Fields: Blood Bank ID, Name, Address, Contact No.

4. **Donate**  
   Fields: Donate ID, Donor ID, Date, Blood Bank ID

---

## 🧠 E-R Diagram

- Entities:
  - Patient
  - Donor
  - Blood Bank
  - Donation
- Relationships:
  - One-to-many between Blood Bank and Donation
  - One-to-many between Donor and Donation

*(Diagram visual not included – can be uploaded separately as an image in assets)*

---

## 🛠️ Functional Elements

- **Insertions**: Data added to all tables to simulate real-world scenarios
- **Procedure**: Automates blood donation record handling
- **Function**: Retrieves specific information, e.g., eligible donors
- **Trigger**: Ensures integrity on blood donation event

---

## ✅ Normalization

| Table       | 1NF | 2NF | 3NF | Notes                                                                 |
|-------------|-----|-----|-----|-----------------------------------------------------------------------|
| Patient     | ✔️  | ✔️  | ❌  | Transitive dependency between contact/address and name               |
| Donor       | ✔️  | ✔️  | ❌  | Same as patient table                                                |
| Blood Bank  | ✔️  | ✔️  | ✔️  | All attributes fully dependent on primary key                        |
| Donate      | ✔️  | ✔️  | ❌  | Transitive dependencies resolved by referencing foreign keys         |

---

## 📸 Sample Output Snapshots (from SQL)

- **Patient Table**
- **Donor Table**
- **Blood Bank Table**
- **Donate Table**
- Execution of Procedure, Function, Trigger

*(Add screenshots in `/assets` folder for GitHub rendering)*

---

## 💾 Tech Stack

| Component | Technology |
|-----------|------------|
| DBMS      | MySQL / Oracle SQL |
| Interface | SQL Editor / Terminal |
| Language  | SQL (DDL, DML, PL/SQL) |

---

## 🧑‍💻 Contributors

- Menpal Dhundhara (302303019)  
- Surbhi Chauhan (302303015)

---

## 📜 License

This project is for academic use and not licensed for commercial distribution.

---

## 🙋‍♀️ About Us

We're final-year MSc Mathematics & Computing students with an interest in **database design, query optimization, and data modeling**. This project showcases practical implementation of ER modeling and SQL techniques.

🔗 [LinkedIn](https://linkedin.com/in/yourprofile)  
📂 [GitHub Portfolio](https://github.com/yourusername)

---

📄 See the full project report in `projectabc.docx`.

