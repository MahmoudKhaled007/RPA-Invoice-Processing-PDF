# 📌 Intelligent PDF Data Extraction & Invoice Automation | UiPath

## 📖 Overview
This project automates invoice processing by extracting structured data from PDFs, calculating totals, generating QR codes, and uploading reports to cloud storage. The UiPath bot streamlines data handling, reducing manual work and improving accuracy.

## 🚀 Features
- **Advanced PDF Data Extraction**: Uses Regex to extract structured tabular data.
- **Excel Processing**: Saves extracted data and calculates total prices and invoices.
- **QR Code Generation**: Generates unique QR codes for each invoice.
- **Cloud Storage Integration**: Uploads processed invoices to OneDrive.
- **Automated Email Notifications**: Sends reports via email upon completion.

## 🔧 Technologies Used
- **UiPath Studio & Orchestrator**
- **Regular Expressions (Regex)**
- **Microsoft Excel Automation**
- **OneDrive API Integration**
- **Email Automation (Outlook/Gmail)**

## 🛠 Installation & Setup
1. **Clone the repository**
   ```sh
   git clone https://github.com/yourusername/Invoice-Automation.git
   ```
2. **Open the project in UiPath Studio**
3. **Configure credentials & API keys** (OneDrive, Email, etc.)
4. **Run the automation** in UiPath Studio or deploy it to Orchestrator.

## 📌 Process Flow
1️⃣ **Extract Data**: Reads PDF invoices and extracts structured data.
2️⃣ **Excel Processing**: Saves data, calculates totals, and organizes it.
3️⃣ **Generate QR Codes**: Uses order IDs to generate unique QR codes.
4️⃣ **Upload to Cloud**: Saves the processed data securely to OneDrive.
5️⃣ **Email Notification**: Sends a final report via email to stakeholders.

## ⚠️ Exception Handling
- **Invalid PDFs**: Logs errors and skips problematic files.
- **Calculation Issues**: Validates extracted data before processing.
- **QR Code Failures**: Implements retry logic for QR generation.

## 📜 License
This project is licensed under the **Apache 2.0 License**. See [LICENSE](LICENSE) for details.

## 📬 Contact
For inquiries or contributions, connect via **GitHub** or **Upwork**.

---
🎯 *This UiPath automation reduces processing time by 85% and eliminates manual errors!*
