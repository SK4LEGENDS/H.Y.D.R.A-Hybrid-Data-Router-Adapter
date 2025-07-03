#  H.Y.D.R.A – Hybrid Data Router & Adapter

> A bi-directional data migration system for Excel and Supabase, powered by UiPath automation workflows.

---

## 📌 Description

**H.Y.D.R.A (Hybrid Data Router & Adapter)** is a robust automation-based solution that enables **two-way data migration** between **Excel spreadsheets** and **Supabase**. Designed using **UiPath workflows** and **REST APIs**, H.Y.D.R.A provides a fast, secure, and structured way to route data across platforms.

---

## 🧰 Tech Stack

- **UiPath** – Automation platform for workflow design  
- **Supabase** – Open-source backend (PostgreSQL, RESTful API)  
- **Microsoft Excel** – Data source and destination  
- **REST API** – For dynamic and secure communication

---

## 🚀 Features

- 🔁 Bi-directional sync between Excel and Supabase  
- 🧠 Intelligent data mapping (columns, data types)  
- 🛠️ Modular UiPath workflows for flexibility  
- 🧾 Ideal for audits, reporting, and migrations  
- 🔐 Secured with Supabase API authentication

---

## 📸 Screenshots

> *(Add your screenshots in the `images/` folder and update the paths below)*

1. **UiPath Workflow Overview**  
   ![Workflow](/Flowchart.jpg)

2. **Flow of data moving from Excel tp Supabase**  
   ![Excel](/Excel_to_Supabase.jpg)

3. **Flow of data moving from Supabase to Excel**  
   ![Supabase](/Supabase_to_Excel.jpg)

4. **Excel Database**  
   ![Log](/Excel.jpeg)

5. **Supabase Database**  
   ![API](/Supabase.jpeg)

---

## ⚙️ Setup & Usage

- Make sure the following **UiPath packages** are installed:
  - `UiPath.Excel.Activities`  
  - `UiPath.System.Activities`  
  - `UiPath.WebAPI.Activities`

- ⚠️ You will need to enter your own:
  - **Endpoint URL**
  - **Authorization header**
  - **API key**

> 🔧 **Note:** If these are missing, UiPath will show validation errors — don’t worry! Once valid values are added, the warnings will go away.

