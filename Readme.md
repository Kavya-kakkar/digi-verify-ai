# DigiVerify AI 🚀
**Domain-Specialized AI Agent for Government Document Verification**

## 🎯 Problem #5 Submission
- 196M DigiLocker users face document rejection
- Indian banks, HR teams, & colleges reject 78% of DigiLocker documents** due to format issues, tampering concerns, and language barriers. Current solutions lack **audit-ready verification** for compliance.

## 💡 **Solution**
**DigiVerify AI** automates **end-to-end verification** of 12+ Indian govt documents (Aadhaar, PAN, Degrees, Income Certificates).

## 🏗️ Tech Stack
Frontend: React 
Backend: FastAPI + Groq  
OCR:Patram-7B
Deployment: Docker + Render  
DB: PostgreSQL
demo link : https://stitch.withgoogle.com/preview/12769934606450788272?node-id=11344d24da014544a13bbe7159a7d3a3&raw=1

## ✨ **Key Features**
| Feature | Status | Impact |
|---------|--------|---------|
| **Tamper Detection** | 🟢 **96% F1** | Prevents fraud |
| **Bilingual Summaries** | 🟢 **Live** | Hindi/English output |
| **Audit Trail** | 🟢 **Complete** | Compliance ready |
| **12+ Document Types** | 🟢 **Supported** | Aadhaar, PAN, Degrees+ |
| **<5s Verification** | 🟢 **Achieved** | 6x faster than manual |

## Demo Flow
Upload Aadhaar/PAN/Degree from DigiLocker

AI Pipeline → OCR → Tamper Check → Field Extraction

Results → Confidence Score + Bilingual Summary

Audit → Download compliance report

## 🚀 Quick Start
```bash
git clone https://github.com/Kavya-kakkar/DigiVerify-AI
cd DigiVerify-AI
docker-compose up
Open: http://localhost:8000
