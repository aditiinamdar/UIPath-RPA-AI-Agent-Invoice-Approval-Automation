# Invoice Approval Automation Bot (UiPath)

This project is an end-to-end RPA workflow built using UiPath Studio Web and Automation Cloud.

The automation monitors a Google Drive folder for new invoices, extracts key data from PDF invoices, and uses AI decision logic to determine whether the invoice should be approved or flagged for review.

## Features
- Monitors Google Drive for new invoice files
- Downloads and processes PDF invoices
- Extracts key invoice fields:
  - Vendor Name
  - Invoice Number
  - Invoice Date
  - Total Amount
- Uses AI decision logic to classify invoice status
- Sends invoice for approval or review

## Tech Stack
- UiPath Studio Web
- UiPath Automation Cloud
- Document Understanding
- Google Drive Integration
- AI Decision Activities

## Project Workflow
1. Detect new invoice in Google Drive
2. Download invoice file
3. Extract invoice details
4. Evaluate approval criteria
5. Return invoice status (Approved / Review)

## Author
Aditi Inamdar
