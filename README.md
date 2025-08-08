# threat-hunting-splunk
Simulated SOC Threat Hunting Lab using Splunk to detect IOCs, triage alerts, and create response reports.
# Threat Hunting – Splunk SIEM

## Overview
Simulated a Security Operations Center (SOC) threat-hunting exercise using Splunk SIEM. The goal was to detect Indicators of Compromise (IOCs), triage alerts, and respond to incidents.

## Tools Used
- Splunk (Free version)
- Sample Network Logs (Simulated)
- Markdown (for report formatting)

##  Project Structure

📁 logs

  └── simulated_logs.csv  
📁 queries  
  └── ioc_queries.spl  
📁 report  
  └── SOC_Report.pdf  
📄 README.md  

## How It Works
- Ingested sample network logs into Splunk.
- Built SPL queries to detect IOCs (suspicious IPs, processes, domains).
- Triaged alerts and created incident response summaries.
- Wrote a post-hunt analysis with recommendations.

## Report
📄 [Threat Hunting Project Summary (PDF)](reports/Threat_Hunting_Summary_Splunk_SIEM.pdf)

## Disclaimer
This is a simulated educational project using test data.
