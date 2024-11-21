# **Secure DevOps Pipeline for Application Deployment**  
*Duration: October 2024 – November 2024*  

## **Overview**  
This project demonstrates a secure CI/CD pipeline for deploying a Python-based web application. Using **Docker**, **AWS CodePipeline**, and advanced DevOps tools, the pipeline ensures secure deployment, container management, vulnerability scanning, and real-time monitoring, making it a robust solution for modern application deployment.  

---

## **Features**  
- **DevOps Pipeline Development**:  
  Set up a secure **CI/CD pipeline** using **AWS CodePipeline**, automating the build, test, and deployment processes.  
- **Containerization & Management**:  
  Deployed and managed application containers using **Docker**, **Docker Compose**, and **Portainer**, ensuring efficient monitoring and secure access control.  
- **Secure File Storage**:  
  Integrated **NextCloud** with **PostgreSQL** for secure, self-hosted cloud storage, enhancing data privacy and accessibility.  
- **Security Vulnerability Scanning**:  
  Utilized **Clair** to scan container images for vulnerabilities, ensuring security throughout the pipeline.  
- **Threat Modeling**:  
  Applied **STRIDE** methodology using the **Microsoft Threat Modeling Tool** to identify and mitigate security risks in the application’s architecture.  
- **Automated Monitoring**:  
  Configured **AWS CloudWatch** for logging and monitoring, providing real-time insights into system performance and security.  

---

## **Technologies Used**  
- **DevOps Tools**: Docker, Docker Compose, AWS CodePipeline, Portainer  
- **Security Tools**: Clair, Microsoft Threat Modeling Tool  
- **Database**: PostgreSQL  
- **Cloud Storage**: NextCloud  
- **Monitoring**: AWS CloudWatch  

---

## **Installation & Setup**  

### **Prerequisites**  
- Docker and Docker Compose installed on the host machine.  
- Access to AWS services (CodePipeline, CloudWatch).  
- PostgreSQL database for NextCloud configuration.  

### **Steps**  
1. Clone the repository:  
    ```bash  
    git clone https://github.com/your-username/secure-devops-pipeline.git  
    cd secure-devops-pipeline  
2. Deploy NextCloud and PostgreSQL using Docker Compose:

    ```bash 
    docker-compose up -d  
3. Configure AWS CodePipeline for automated build and deployment.

4.  Run vulnerability scans with Clair:

    ```bash 
    clair-scanner --ip <your-ip> nextcloud-image  
5. Monitor logs and metrics using AWS CloudWatch.

## Key Skills Demonstrated
Secure DevOps Practices
Containerized Environment Management
CI/CD Automation
Threat Modeling & Risk Mitigation
Vulnerability Management
Cloud-Based Monitoring & Logging
## Project Outcomes
Automated deployment processes, reducing manual effort and errors.
Enhanced application security by integrating continuous vulnerability scanning and threat modeling.
Real-time monitoring and secure containerized environments for scalable deployments.
## Contributors
Sanjana Jayaram Mottemmal
DevOps Engineer | Cybersecurity Specialist
## License
This project is licensed under the MIT License - see the LICENSE file for details.
