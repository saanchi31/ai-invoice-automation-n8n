# ai-invoice-automation-n8n
🚀 Built to automate invoice processing and solve real-world API delay issues using n8n and AI.
A simple yet practical automation workflow that processes PDF invoices using n8n and AI, extracts structured data, and stores it in Google Sheets with automated notifications.


## 🚀 Workflow Overview

- Upload a PDF invoice to Google Drive
- Trigger activates automatically
- Wait node ensures file availability
- File is downloaded and processed
- Invoice data is extracted using AI
- Data is stored in Google Sheets
- Email notification is sent


## 🛠️ Tech Stack

- n8n
- Google Drive API
- Google Sheets
- OpenAI API
- Gmail API


## ⚠️ Challenge Faced

While building this workflow, I encountered an issue where newly uploaded files were not immediately accessible through the Google Drive API.

This caused the workflow to fail with a "File not found" error, even though the file was successfully uploaded.

### ✅ Solution

Added a Wait node (5–10 seconds) before downloading the file to ensure it is fully available.



## 📸 Screenshots
    n8n workflow
<img width="1919" height="978" alt="Screenshot 2026-04-22 195701" src="https://github.com/user-attachments/assets/d0fcbd96-3da3-4674-b159-c62a6263d1bc" />

    google drive 
<img width="1429" height="495" alt="Screenshot 2026-04-22 201718" src="https://github.com/user-attachments/assets/be528d5a-49b3-4331-abfa-7088fb9e67c0" />

    google sheet
 <img width="1919" height="485" alt="Screenshot 2026-04-22 201740" src="https://github.com/user-attachments/assets/33f20d1f-d162-4740-90ce-23fabe7123f0" />
<img width="1763" height="307" alt="Screenshot 2026-04-22 201756" src="https://github.com/user-attachments/assets/67ebe8f3-a710-4cc3-a713-6df4d09d6995" />

    email notification 
<img width="1475" height="713" alt="Screenshot 2026-04-22 201831" src="https://github.com/user-attachments/assets/dcbf246d-7d90-470c-9a39-1320bdfee64f" />




## 💡 Learnings

- Handling real-world API delays
- Working with automation workflows
- Using AI for data extraction


## 🌟 Highlights

- Built a complete end-to-end automation workflow  
- Solved a real-world system delay issue  
- Integrated AI with automation tools  
- Designed a practical use-case (invoice processing)  


## 📌 Future Improvements

- Add support for multiple invoice formats  
- Improve data accuracy with better AI prompts  
- Build a frontend dashboard for viewing data  
- Integrate with databases instead of Google Sheets  
