# Email Scraper - Colab Project

This project is a Google Colab notebook designed to **scrape emails** and automatically store them in a connected **Google Sheet**.  
It demonstrates skills in Python automation, server authentication, and cloud integration.

---

## 🚀 Features
- Scrapes email leads from configured sources.
- Requires server details (email server, email address, and password).
- Saves results directly into a Google Sheet stored in Google Drive.
- Easy to adapt for different scraping workflows.

---

## ⚙️ Setup Instructions
1. Open the notebook in Google Colab.
2. Provide the following configuration values:
   - **Email server** (e.g., IMAP/SMTP host)
   - **Email address**
   - **Password**
   - **Google Sheet name** (must be created in Google Drive and shared with this notebook’s service account)
3. Run the notebook cells to start scraping and saving results.

---

## 📂 Output
- Scraped emails are automatically written into the specified Google Sheet.
- The sheet can be shared or exported for further analysis.

---

## 💼 Portfolio Note
This project highlights:
- **Python scripting in Colab**
- **Data scraping and automation**
- **Integration with Google Drive/Sheets**
- **Secure handling of credentials**

---

## 🔗 Example
If your Google Sheet is named `EmailLeads`, ensure it is shared with the Colab runtime service account before running the script.
