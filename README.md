🚀 AWS Automated Receipt Generator | Serverless Project

A **serverless system** on AWS that automatically extracts, stores, and emails receipt details, eliminating manual data entry. Built after **AWS Cloud Practitioner Certification** to showcase hands-on cloud skills.

---

## 💡 Overview

1. **Upload Receipt** → PDF/Image uploaded to **S3** triggers a Lambda function.  
2. **Extract Data** → **Amazon Textract** reads vendor, date, total, and items.  
3. **Store Data** → Structured data saved in **DynamoDB**.  
4. **Send Notification** → **Amazon SES** emails extracted receipt details.  


## 🧩 AWS Services Used

| Service | Role |
|---------|------|
| S3 | Receipt storage & event trigger |
| Lambda | Serverless backend orchestration |
| Textract | OCR-based data extraction |
| DynamoDB | NoSQL structured storage |
| SES | Email notifications |

---

## 🔒 Security & Reliability

- IAM roles with **least privilege**  
- S3 & DynamoDB **encryption**  
- CloudWatch logging & monitoring  
- Optional dead-letter queue for failed events


## 🌱 Future Enhancements

- Dashboard to view receipts  
- Expense analytics with QuickSight  
- Integration with Tally/Zoho Books


## 📸 Screenshots

**S3:** Receipt Upload | Incoming Folder | Object Creation  
**DynamoDB:** Table Info | Table Creation  
**Lambda:** Function Creation | Flow  
**SES:** Verification  
**Output:** Email Notification  



## 📂 Project Files

- `lambda.py` → Lambda function  
- Screenshot folders: `S3/`, `dynamodb/`, `lambda/`, `ses/`, `output/`


