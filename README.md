# GCP File Upload Service  
[![Deploy on GCP](https://img.shields.io/badge/Deploy%20on-Google%20Cloud-blue)](https://console.cloud.google.com)  
A scalable cloud storage system built during my internship, handling **10K+ daily uploads** with virus scanning and cost optimization.  

---

## **Features**  
- **Secure File Uploads**: Scan files for malware using ClamAV (99.9% detection rate).  
- **GCP Integration**: Store files in Google Cloud Storage with metadata in PostgreSQL.  
- **Cost Reduction**: 30% lower cloud costs via Compute Engine autoscaling.  
- **Collaboration**: Built with a 4-member team using Agile/Scrum.  

---

## **Tech Stack**  
- **Backend**: Node.js, Express  
- **Database**: PostgreSQL (metadata)  
- **Cloud**: GCP (Cloud Storage, Compute Engine)  
- **Security**: ClamAV, JWT  
- **Tools**: Docker, GitHub Actions, Postman  

---

## **Setup & Installation**  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/Manaswini-wq/file-upload-service.git  
