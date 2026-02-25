# Automated B2B Lead Qualification & Routing System

![Workflow](workflow.png)

## Overview

This project is an automated lead qualification and routing workflow built using n8n.  
It simulates a real-world B2B sales intake pipeline by automatically filtering, classifying, and routing incoming leads.

---

## Problem

Sales teams often spend significant time reviewing unqualified leads submitted through online forms.  
Manual filtering delays response time and reduces overall efficiency.

---

## Solution

This workflow automates the lead intake and qualification process by:

- Capturing lead data through a form
- Storing submissions in Google Sheets
- Filtering personal email domains (Gmail, Yahoo, Outlook)
- Classifying leads based on company size
- Sending automated qualification emails
- Updating lead status (Hot / Mid / Cold)

---

## Lead Classification Logic

- 200+ employees → Hot  
- 100–199 employees → Mid  
- Less than 100 employees → Cold  

The routing logic is implemented using conditional nodes (If / Switch) within n8n.

---

## Tech Stack

- n8n
- Google Sheets API
- Gmail API
- Conditional Logic (If / Switch)
- Workflow Automation

---

## Business Impact

This system reduces manual lead filtering, improves response time, and demonstrates how workflow automation can support scalable sales operations.
---

## Author
Salma Alahmad
