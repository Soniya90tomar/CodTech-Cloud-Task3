# CodTech Internship – Task 3: Multi-Cloud Architecture

## ✅ Task Overview
This task demonstrates a simulated multi-cloud architecture where services are distributed between AWS and GCP for high availability, cost optimization, and better performance.

## 🏗 Architecture Overview
- **AWS S3**: Stores static website files and application assets
- **AWS Lambda**: Processes backend logic and API requests
- **GCP Compute Engine**: Runs the application server
- **GCP BigQuery**: Stores and analyzes large datasets
- **APIs**: Used to transfer data between AWS and GCP

## 🔄 Workflow
1. User requests are sent to **GCP Compute Engine**
2. Compute Engine fetches static files from **AWS S3**
3. **AWS Lambda** handles API calls and business logic
4. Data is analyzed and stored in **GCP BigQuery**
5. Results are sent back to the user

## 📸 Architecture Diagram
![Multi-Cloud Architecture](screenshots/multi_cloud_architecture.png )

## ✅ Benefits of Multi-Cloud
- Avoid vendor lock-in
- Improve disaster recovery
- Optimize performance by using best services from each provider

## 🚀 Conclusion
This submission fulfills Task 3 by simulating a multi-cloud architecture between AWS and GCP, demonstrating service interoperability without requiring paid cloud access.
