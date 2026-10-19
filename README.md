# 🚀 Office LTSC 2024 Deployment Script

This repository contains an XML configuration file to perform an automated **Clean Install** of **Microsoft Office LTSC Professional Plus 2024** using the official Microsoft method: **Office Deployment Tool (ODT)**.

This script is optimized to install only the core applications (Word, Excel, PowerPoint) without *bloatware*, ensuring a lightweight and efficient installation.

## 📋 Configuration Specifications
The `configuration.xml` included in this repo is set with the following parameters:
- **Edition:** Office LTSC Professional Plus 2024 (Volume License)
- **Version:** PerpetualVL2024 (One-time purchase / Non-Subscription)
- **Architecture:** 64-bit
- **Included Apps:** Word, Excel, PowerPoint.
- **Excluded Apps:** Outlook, Publisher, Access, OneDrive, Teams, Skype.

## 🛠️ Usage Instructions

### 1. Preparation
1. Download the latest **Office Deployment Tool (ODT)** from the official Microsoft website.
2. Extract the downloaded file and keep only `setup.exe`.
3. Place `setup.exe` and the `configuration.xml` file from this repository into the **same folder**.

### 2. Download Source Files
Open Command Prompt (CMD) as **Administrator**, navigate to the folder location, and execute the following command:

```cmd
setup.exe /download configuration.xml

setup.exe /configure configuration.xml
