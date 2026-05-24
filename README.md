# Finance Anomaly Detector
An n8n workflow that automatically scans 1,000 financial 
transactions and flags suspicious ones using Google Sheets.

## What it does
- Reads transactions from Google Sheets
- Flags failed transactions, missing data, low accuracy scores
- Outputs flagged transactions as a CSV report
