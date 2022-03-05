# Azure-Sentinel-SIEM-
# Project Description:
 We are deploying Azure Sentinel, a cloud-based SIEM, as well as a virtual machine in the cloud that will serve as our honeypot. We're going to make it extremely vulnerable to internet attacks. Then, essentially, we'll monitor and log a large number of attacks from various IP addresses from various countries all over the world. We'll take that data and plot it on a map so we can see where all of the attacks are coming from.
# Created content for, and performed the following tasks for, Azure Sentinel (SIEM):
# Used custom powershell script to extract metadata from Windows event viewer to be forwarded to third party API in order to derive geolocation data
# Setup log analytics workspace in Azure to ingest custom logs containing geographic information (Latitude, longitude, state, and country)
# Created custom fields in log analytics workspace with the intent of mapping geo data in azure sentinel
# Configured azure sentinel (Microsoft Cloud SIEM) workbook to display global attack data (RDP Brute Force) on world map according to physical location and magnitude of attacks
