# Client Cloud Recommendations & Decision Matrix

## Client Recommendations

**Client A – Startup Company**
* **Recommended Platform:** AWS
* **Justification:** AWS is ideal for startups due to its AWS Activate program, flexible pay-as-you-go pricing, and rapid scalability. Its mature ecosystem enables early-stage companies to launch quickly without significant upfront infrastructure investments.
* **Key Services:** AWS Amplify, Amazon Cognito, Amazon DynamoDB.

**Client B – University**
* **Recommended Platform:** Microsoft Azure
* **Justification:** Azure provides seamless hybrid integration with the university's existing infrastructure, including Active Directory, Windows Server, and Microsoft 365. This minimizes operational complexity by extending identity management straight into the cloud via Microsoft Entra ID.
* **Key Services:** Microsoft Entra ID, Azure Virtual Machines, Azure SQL Database.

**Client C – AI Research Company**
* **Recommended Platform:** Google Cloud Platform (GCP)
* **Justification:** GCP offers specialized hardware such as Tensor Processing Units (TPUs) and specialized machine learning pipelines. Its platform excels at high-performance computing and scaling complex data science workflows efficient for AI research.
* **Key Services:** Vertex AI, Google Compute Engine (TPU pods), BigQuery.

**Client D – Global E-Commerce Company**
* **Recommended Platform:** AWS
* **Justification:** AWS provides unmatched global availability zones, auto-scaling capabilities, and low-latency Content Delivery Networks via CloudFront. These capabilities ensure reliable performance and uptime during massive global traffic surges.
* **Key Services:** Amazon EC2 Auto Scaling, Amazon CloudFront, Amazon Aurora.

---

## Multi-Cloud Decision Matrix

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | AWS | Extensive credit programs, flexible scale, and rapid time-to-market tools. |
| **Enterprise Organization** | Microsoft Azure | Seamless integration with existing on-premises Windows and enterprise IT setups. |
| **Microsoft Environment** | Microsoft Azure | Direct integration with Active Directory, Microsoft 365, and Windows Server licenses. |
| **AI / Machine Learning** | Google Cloud Platform | Native TPU hardware, specialized ML tools, and data processing power. |
| **Kubernetes Deployment**| Google Cloud Platform | Creator of Kubernetes; offers Google Kubernetes Engine (GKE). |
| **Global Web Application**| AWS | Expansive network of Availability Zones and CloudFront edge locations. |

---
### References
* Amazon Web Services. (2026). *AWS Architecture Center*. https://aws.amazon.com/architecture/
* Microsoft. (2026). *Azure Solution Architectures*. https://learn.microsoft.com/en-us/azure/architecture/
* Google Cloud. (2026). *Google Cloud Solutions Architecture*. https://cloud.google.com/solutions