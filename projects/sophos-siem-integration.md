Sophos Central API Integration with Cloud SIEM

Project Overview
Integrated Sophos Central security alerts into a cloud-based SIEM (Security Information and Event Management) system using REST APIs for centralized monitoring and threat detection.

 Key Objectives
- Automate alert collection from Sophos Central endpoint protection
- Normalize security data for SIEM ingestion
- Create a centralized dashboard for security monitoring
- Reduce manual log review through automation

Technologies Used
- Sophos Central API 
- Cloud SIEM Platform Wazuh Cloud
- HTTP/HTTPS protocol
-
-   Project Documentation
This project is fully documented with step-by-step implementation:

View Complete Project Documentation: https://drive.google.com/drive/folders/18ZO8dQY7e_aAHsCqGfbE6xC9eVrPlsEI?usp=drive_link



Key Implementation Steps
1. API Setup: Registered application in Sophos Central and obtained API credentials
2. Data Extraction: Created Python script to pull security alerts with filters
3. Data Transformation: Mapped Sophos alert fields to Common Event Format (CEF)
4. SIEM Configuration: Set up HTTP data collector in cloud SIEM
5. Testing & Validation: Verified alert ingestion and created detection rules

 Skills Demonstrated
- API integration and authentication
- Security data normalization
- Cloud SIEM configuration
- Python scripting for security automation
- Understanding of EDR-to-SIEM workflows

 Related Resources
- [Sophos Central API Documentation](https://developer.sophos.com/)
- [SIEM Data Ingestion Best Practices](link-to-helpful-resource)
