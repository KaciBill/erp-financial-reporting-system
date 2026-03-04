# ERP Financial Reporting & Accounting Automation System

## Project Overview
This project simulates a simplified ERP financial system similar to SAP or Oracle Financials. 
The system integrates operational datasets including sales, payroll, loans, and banking 
transactions into a centralized General Ledger used for financial reporting and analysis.

The objective is to demonstrate financial systems design, accounting workflow automation, 
and BI reporting.

## Business Problem
Organizations need integrated systems that transform operational transactions into 
financial reporting. This project demonstrates how operational data flows through 
ERP modules into accounting and reporting systems.

## System Architecture

Customers
   │
   ▼
Sales System (Sales Transactions Dataset)
   │
   ▼
Revenue Journal Entries
   │
   ▼
=========================
      GENERAL LEDGER
=========================
   ▲        ▲        ▲
   │        │        │
Payroll   Treasury   Inventory
System     / Loans     System
   │        │        │
   ▼        ▼        ▼
Payroll   Loan &   Cost of Goods
Expense   Interest      Sold
Entries    Entries
            │
            ▼
     Financial Statements
     (Income Statement,
      Cash Summary)
            │
            ▼
      Power BI Dashboard
