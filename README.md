# Courier-Cost-Optimization
📦 Courier Cost Optimization & Logistics Management System
📋 Project Overview

Designed and implemented a data-driven courier cost optimization framework for a manufacturing organization to reduce domestic courier expenses, standardize dispatch operations, and improve shipment visibility.

The project combines logistics cost analysis, courier rate comparison, volumetric weight calculations, shipment SOPs, ERP integration, and operational governance to enable data-driven courier decision-making while ensuring accurate billing and improved process compliance. The SOP and workflow emphasize ERP entry, shipment verification, billing rules, pickup cutoffs, and audit controls.

🚩 Business Problem

The organization was facing several logistics challenges:

High courier expenses due to incorrect carrier selection
Incorrect billing because of volumetric weight calculations
No standardized courier selection process
Lack of shipment visibility
Manual dispatch process
Poor invoice verification
No centralized courier costing model
Limited reporting for logistics expenses
Delays due to inconsistent dispatch procedures
🎯 Project Objectives
Reduce domestic courier cost
Standardize shipment process
Automate courier costing
Compare courier pricing across delivery zones
Optimize box selection
Minimize billing errors
Improve dispatch accuracy
Increase shipment visibility
Establish logistics governance
📊 Dataset

The project uses multiple operational datasets including:

Courier Rate Cards
Air Pincode Mapping
Surface Pincode Mapping
Transit Time (TAT) Database
Courier Pricing Matrix
Domestic Cost Analysis
ERP Shipment Records
Courier Invoice Records
📦 Business Rules Implemented
Billable Weight

Billable weight is calculated as:

Billable Weight = MAX(Actual Weight, Volumetric Weight)

Volumetric Weight Formula

Air Courier

(L × B × H) / 5000

Surface Courier

(L × B × H) / 4750

Documents follow the air divisor, and the landed cost also accounts for per-kg rates, fuel surcharge, and GST.

📈 Operational Metrics

The project evaluates:

Actual Weight
Volumetric Weight
Billable Weight
Courier Cost
Fuel Surcharge
GST
Total Landed Cost
Cost per Shipment
Transit Time (TAT)
Dispatch Accuracy
Cost Savings
Invoice Accuracy
Delivery Performance
⚙️ Solution Developed
1. Courier Costing Engine

Automated calculation of:

Actual Weight
Volumetric Weight
Chargeable Weight
Courier Charges
GST
Fuel Surcharge
Final Payable Amount
2. Courier Selection Model

Selects the most economical courier based on:

Destination Pincode
Service Type
Transit Time
Zone
Courier Rates
Billable Weight
3. Shipment SOP

Standardized workflow including:

ERP Entry
Shipment Verification
Reception Validation
Invoice Generation
Courier Pickup
Daily Dispatch Timeline

The SOP requires ERP logging of dimensions, weight, purpose, and customer details before reception verification and courier handoff.

4. Invoice Verification Model

Cross-verifies:

Actual Weight
Chargeable Weight
Courier Rates
Invoice Amount
Service Charges

to detect billing discrepancies.

5. Courier Governance

Implemented:

Pickup Cutoff Rules
Escalation Matrix
Dispatch SOP
Responsibility Matrix
Audit Process

The process enforces shipment readiness before the 5:00 PM pickup, reception control, and escalation/audit practices to improve transparency.

📊 Dashboard KPIs
Total Shipments
Total Courier Cost
Average Cost per Shipment
Air vs Surface Distribution
Zone-wise Cost
Courier-wise Spend
Transit Time Analysis
Invoice Accuracy
Dispatch Compliance
Monthly Cost Trend
Cost Savings
Delivery SLA
📉 Business Impact
Standardized courier dispatch process
Reduced manual calculation errors
Improved billing transparency
Optimized courier selection
Better logistics cost visibility
Improved shipment tracking
Faster invoice verification
Reduced operational delays
Stronger audit compliance
🛠️ Tools & Technologies
Microsoft Excel
Advanced Excel
Pivot Tables
Power Query
IF Functions
INDEX MATCH
SUMIFS
Data Validation
Conditional Formatting
Google Sheets
ERP System
Logistics Cost Analysis
📂 Repository Structure
📁 Courier-Cost-Optimization
│
├── README.md
├── DTDC Costing Model.xlsx
├── Air Pincode Mapping.xlsx
├── Surface Pincode Mapping.xlsx
├── Domestic Cost Analysis.xlsx
├── Courier SOP.pdf
├── Courier Training Presentation.pptx
└── Images/
⭐ Key Learning Outcomes
Logistics Cost Optimization
Procurement Analytics
Supply Chain Operations
Courier Cost Modeling
Transportation Cost Analysis
SOP Development
Invoice Auditing
ERP Process Design
Business Process Optimization
Operational Analytics
📌 Project Highlights

✔ Developed an end-to-end courier costing model using Excel and logistics business rules.

✔ Standardized shipment dispatch through a structured SOP with ERP integration, reception verification, and defined pickup timelines.

✔ Implemented automated volumetric weight calculations and optimized courier selection based on destination, service type, and cost.

✔ Created invoice audit and governance processes to improve billing accuracy and operational transparency.
