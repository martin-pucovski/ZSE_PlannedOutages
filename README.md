# ZSE Planned Outages Notification System

## Project Overview
This automation solution monitors the ZSE (Západoslovenská energetika) website for planned power outages in a specified city and street. If an outage is detected, an email notification is automatically sent to the user.

## Prerequisites
To use this solution, you will need the following:
- Basic understanding of how to run UiPath robots.
- Installed software:
  - **UiPath Robot**
  - **Google Chrome**

## Setup Instructions

### 1. Orchestrator Asset Configuration
Create the following assets in UiPath Orchestrator to store necessary configuration data:

- **Asset Name:** `Folder_Data`  
  **Type:** Text  
  **Description:** This asset stores the absolute path on your machine where the `Data` folder is located.

- **Asset Name:** `Mail_NoReply`  
  **Type:** Credential  
  **Description:** This asset stores the credentials used to send email notifications.

### 2. Configuration File (Config.xlsx)
Review and update the `Config.xlsx` file as needed. Customize the fields and values to match your environment and preferences.

## Running the Automation
1. Deploy the project to your UiPath Orchestrator.
2. Trigger the process to begin monitoring for planned power outages in your selected location.
