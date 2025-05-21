
# 📚 Campus Complaint Management System

A cloud-integrated web platform where students can submit campus-related complaints (e.g., broken benches, PC malfunction) and campus authorities can centrally manage and resolve them. The system leverages Microsoft Azure services for authentication, storage, notifications, deployment, and monitoring.

## 🚀 Features

- 👨‍🎓 **Student/Admin Login** – Role-based login system via Azure Entra ID.
- 📝 **Complaint Submission Portal** – Students can submit detailed complaints with optional image attachments.
- 📊 **Student Dashboard** – View the status and history of all submitted complaints.
- 📬 **Automated Email Notifications** – Students receive emails upon complaint resolution.
- 🗂️ **Admin Panel** – View, assign, and resolve student complaints centrally.

## 🌐 Azure Services Used

| Azure Service              | Purpose                                                                 |
|---------------------------|-------------------------------------------------------------------------|
| **Azure Entra ID**         | Secure authentication for students and admins                          |
| **Azure Blob Storage**     | Store uploaded complaint images                                         |
| **Azure SQL Database**     | Store structured complaint data                                         |
| **Azure Logic Apps**       | Automate email acknowledgments and resolution notifications             |
| **Azure App Service**      | Host the Flask-based web application                                    |
| **Azure DevOps Pipelines** | Enable CI/CD for seamless build and deployment                          |
| **Azure Application Insights** | Monitor application performance and error tracking                |

## 🛠️ Tech Stack

- **Frontend**: HTML, CSS, JavaScript  
- **Backend**: Python (Flask)  
- **Database**: Azure SQL  
- **DevOps**: Azure Pipelines  
- **Deployment**: Azure App Service

## 📁 Project Structure

```
Azure_Project/
├── app.py
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   └── complaint_form.html
├── static/
│   ├── css/
│   └── js/
├── requirements.txt
└── README.md
```

## 🧪 How to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/SameerChn/Azure_Project.git
   cd Azure_Project
   ```

2. Set up a Python virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scriptsctivate
   ```

3. Install dependencies:
   ```bash
   pip install python-dotenv
   pip install -r requirements.txt
   ```

4. Set up environment variables and Azure credentials.

5. Run the application:
   ```bash
   python app.py
   ```

6. Visit `http://localhost:5000` in your browser.

## ✅ Major Outcomes

- Centralized complaint handling improved transparency.
- Automated email notifications streamlined communication.
- Cloud-native architecture ensured scalability and reliability.

## 📌 Project Objective

To simplify and digitize campus complaint workflows using cloud-native solutions while enhancing user engagement through intuitive UI and real-time updates.

## 📎 Related Links

- [🔗 GitHub Repository](https://github.com/SameerChn/Azure_Project)
- [📖 Azure Documentation](https://learn.microsoft.com/en-us/azure/)

## 🌍 Live Demo

🚧 The site is live but authentication is still under development.

🔗 [Campus Complaint Management System (Work in Progress)](https://6604214sameerkumarg1-axehbbcpcmezgbgv.centralindia-01.azurewebsites.net)


## 👨‍💻 Author

**Sameer Kumar**
