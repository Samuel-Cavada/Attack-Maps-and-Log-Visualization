<p align="center">
  <a href="https://github.com/Samuel-Cavada" target="_blank">
    <img src="https://img.shields.io/badge/Back_to_Main_Page-000000?style=for-the-badge&logo=github&logoColor=white" alt="Back to Main Page"/>
  </a>
</p>

<h1 align="center">Attack Maps and Log Visualization</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Azure%20Sentinel-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Cloud Platform" />
  <img src="https://img.shields.io/badge/OS-N/A-0078D6?style=for-the-badge&logo=windows&logoColor=white" alt="OS" />
  <img src="https://img.shields.io/badge/Tool-Azure%20Workbooks-00B388?style=for-the-badge&logo=microsoftazure&logoColor=white" alt="Tool" />
  <img src="https://img.shields.io/badge/Tool-PowerShell-2C5EA8?style=for-the-badge&logo=powershell&logoColor=white" alt="Tool" />
  <img src="https://img.shields.io/badge/Focus-Log%20Visualization-orange?style=for-the-badge" alt="Focus Area" />
</p>

---

## 📌 Project Objective
> Create dynamic world map visualizations using Azure Sentinel Workbooks to showcase security events like authentication attempts and malicious traffic. These visual dashboards help correlate activity with geographic sources and support security monitoring.

---

## 🧰 Tools & Technologies
- **Platform:** Azure Sentinel
- **OS:** N/A
- **Tools:** Azure Workbooks, Log Analytics, PowerShell
- **Languages/Scripts:** KQL

---

## 🧠 Skills Gained / Focus Areas
- Created visual attack maps in Azure Sentinel
- Used KQL queries to extract geolocation data from logs
- Built interactive dashboards for different event types
- Improved situational awareness with global threat views

---

## 🧪 Environment Setup
> Accessed the Azure Portal and navigated to Sentinel. Used the built-in **Workbooks** feature under **Threat Management** to build custom dashboards. Selected logs were queried and converted into geographic visualizations.

![Environment Setup](assets/images/setup.jpg)

---

## 🛠️ Walkthrough
1. [Step 1: Open Workbooks](#step-1-open-workbooks)
2. [Step 2: Select Log Types](#step-2-select-log-types)
3. [Step 3: Build Visual Maps](#step-3-build-visual-maps)

---

### ✅ Step 1: Open Workbooks
> - Logged into Azure Portal  
> - Went to **Microsoft Sentinel**  
> - Navigated to **Threat Management** → **Workbooks**  
> - Clicked **Add Workbook** to begin creating a custom visualization

![Step 1](assets/images/step1.jpg)

---

### ✅ Step 2: Select Log Types
> Chose logs based on security and activity relevance. Focused on logs that included IP geolocation fields for map rendering:

- **Entra ID Authentication Success**
- **Entra ID Authentication Failures**
- **Azure Resource Creation**
- **VM Authentication Failures**
- **Malicious Traffic Entering the Network**

![Step 2](assets/images/step2.jpg)

---

### ✅ Step 3: Build Visual Maps
> - Used map visual elements in the workbook interface  
> - Crafted KQL queries for each scenario to extract source IPs and geolocate them  
> - Applied filters to show time-based events and highlight patterns by region  
> - Finalized dashboards that showed real-time log-based world activity

![Step 3](assets/images/step3.jpg)

---

## 📝 Outcomes and Lessons Learned
- **Technical Insight:** Visualization enhances understanding of log data and attack trends across regions.
- **Configuration Skills:** Gained experience with Sentinel Workbooks and geolocation features.
- **Troubleshooting:** Refined KQL queries to ensure valid IP resolution and mapping.
- **Takeaway:** Visual dashboards support faster threat detection, reporting, and security posture communication.

---

## 📎 References
- [Azure Workbooks Documentation](https://learn.microsoft.com/en-us/azure/azure-monitor/workbooks-overview)
- [Create and Edit Azure Workbooks](https://learn.microsoft.com/en-us/azure/sentinel/tutorial-monitor-your-data)
- [KQL for Map Visuals](https://learn.microsoft.com/en-us/azure/azure-monitor/logs/log-analytics-tutorial)
