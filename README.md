
# Java CD Pipeline using Jenkins 

This project demonstrates a complete **Continuous Delivery (CD)** pipeline for a Java web application.

---

#  Project Objectives

- Build Java web app using **Maven**
- Perform **code quality check** using **SonarQube**
- Store build artifacts in **Nexus Repository**
- Run **Selenium test suite** on a **Windows Jenkins slave**
- Deploy `.war` file to **Tomcat server**
- Send real-time **Slack notifications**
- All hosted on **AWS EC2 free-tier** instances

---

# Tools Used

| Tool        | Purpose |
|-------------|---------|
| Jenkins | CI/CD Orchestration |
| Git     | Version Control |
| Maven   | Build Tool |
| SonarQube | Code Quality Analysis |
| Nexus   | Artifact Repository |
| Selenium | Automated Testing |
| Tomcat  | Application Server |
| Slack   | Notification |
| Windows Jenkins Agent** | Execute test suite |
| AWS EC2 | Hosts all tools |

---

#  Pipeline Flow

1. Code pushed to GitHub
2. Jenkins job triggers automatically
3. Code is built using Maven
4. SonarQube scans code quality
5. WAR file is pushed to Nexus
6. Jenkins deploys WAR to Tomcat
7. Selenium tests run on Jenkins slave (Windows)
8. Slack alert sent for success/failure

---

## 📸 Screenshots

### ✅ Jenkins Build
![Jenkins Build](Screenshots/jenkins-build.png)

### ✅ Nexus Upload
![Nexus Repo](Screenshots/nexus-repo.png)

### ✅ SonarQube Scan
![Sonar](Screenshots/sonarqube-report.png)

### ✅ Slack Notification
![Slack](Screenshots/slack-notification.png)

### ✅ Selenium Test Output
![Selenium](Screenshots/selenium-test.png)

### ✅ App Running
![Login Page](Screenshots/login-page.png)


## 📚 Learning Outcome

- Developed a full CI/CD pipeline from code push to deployment
- Connected Jenkins with SonarQube, Nexus, Selenium, and Tomcat
- Automated WAR builds and versioned uploads to Nexus
- Performed automated testing using Selenium
- Successfully deployed the app to a remote Tomcat server
- Used Slack for team communication and alerting








