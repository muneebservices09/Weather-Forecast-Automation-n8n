# 🌤️ Weather-Forecast-Automation-n8n

![n8n](https://img.shields.io/badge/Workflow-n8n-FF6C37?style=flat&logo=n8n&logoColor=white)
![WeatherAPI](https://img.shields.io/badge/Data-WeatherAPI-00A699?style=flat&logo=icloud&logoColor=white)
![Supabase](https://img.shields.io/badge/Database-Supabase-3ECF8E?style=flat&logo=supabase&logoColor=white)
![SMTP](https://img.shields.io/badge/Delivery-SMTP-blue?style=flat)
![JavaScript](https://img.shields.io/badge/Logic-JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)

---

## 📺 Project Demo
Experience the seamless flow from user submission to personalized environmental reporting.

https://www.loom.com/share/941af541355f459a8f19f6c3e4cda597?sid=1307c447-a23c-45d0-88b9-dba260b51072

---

## 🚀 The Solution: Automating Personal Intelligence
In a world saturated with generic data, this system solves the problem of **fragmented information delivery**. Users often have to manually check multiple apps for weather and air quality, while businesses struggle to collect user data in a way that provides immediate, tangible value.

### 🛑 The Problem
*   **Manual Friction:** Checking weather and AQI manually across different sites is a repetitive, low-value task.
*   **Data Fragmentation:** User requests are often lost or siloed if not captured in a structured database immediately.
*   **Lack of Personalization:** Standard weather applications don't deliver proactive, high-fidelity reports directly to a user's private inbox.

### ✅ The Solution
This workflow functions as an **Autonomous Environmental Agent**. It eliminates manual intervention and provides a high-end service by:
1.  **Instantly Capturing Intent:** Triggering real-time responses from user-facing forms.
2.  **Dynamic Data Enrichment:** Automatically fetching complex environmental metrics (Temperature + Air Quality Index) that users care about most.
3.  **Closing the Value Loop:** Delivering a professional, personalized report via email while simultaneously building a robust lead database in Supabase for the administrator.

---

## 🧠 Core Technical Pillars

### 1. 📥 Event-Driven Ingress (Webhooks)
The system is reactive. Using an asynchronous **Webhook Node**, it listens for incoming data from a frontend form. This ensures that the moment a user hits "Submit," the automation engine begins processing without a single second of delay.

### 2. ⚙️ Logic-Gate Validation (Code Node)
To ensure the system remains professional and error-free, I implemented a **Custom JavaScript Node**. This acts as a quality controller that:
*   Performs automated email syntax validation.
*   Sanitizes and normalizes city names to prevent API failures.
*   Prepares the data schema for downstream processing.

### 3. 🌡️ Real-Time Environmental Synthesis
The workflow interfaces with the **WeatherAPI.com REST API**. It goes beyond basic temperature checks by dynamically extracting the **Air Quality Index (AQI)** and current weather states, providing a layer of health-conscious value to the end-user.

### 4. 🗄️ Relational Persistence (Supabase PostgreSQL)
Unlike simple "send-and-forget" scripts, this system ensures every interaction is saved. By integrating **Supabase**, the workflow archives user details and environmental data into a relational database, allowing for long-term data analysis and user re-engagement.

---

## ✨ Advanced Features (Production Grade)
*   **⚙️ 100% Hands-Free Operation:** Once activated, the system operates 24/7, processing thousands of requests without manual oversight.
*   **🛡️ Schema Enforcement:** Strict database mapping ensures that data integrity is maintained across numeric, boolean, and timestamp fields.
*   **📧 Personalized SMTP Delivery:** The system generates and sends branded, localized HTML emails that provide a premium experience to the recipient.

---

## 🛠️ Technical Stack
| Layer | Technology |
| :--- | :--- |
| **🔄 Automation** | n8n (Orchestration & Logic) |
| **🎨 Frontend** | Lovable Forms (Data Capture) |
| **🔎 Data Source** | WeatherAPI.com (Environmental Intelligence) |
| **💾 Backend** | Supabase (PostgreSQL Database) |
| **📧 Notification** | SMTP (Personalized Delivery) |
| **📜 Scripting** | JavaScript (Validation & Data Cleaning) |

---

## ✍️ Author
**Muneeb Ali Khan**
*   **LinkedIn:** [Muneeb Ali Khan](https://www.linkedin.com/in/muneeb-ali-khan-2a1675365)

---

## 📜 License
This project is licensed under the MIT License.
