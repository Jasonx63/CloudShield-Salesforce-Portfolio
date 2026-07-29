# Sales Workflow

## Overview

This project simulates a complete Salesforce Sales Cloud implementation for a fictional cybersecurity SaaS company, CloudShield Security. The goal was to model the end-to-end B2B sales process, from lead generation through customer acquisition and proposal management.

Rather than creating isolated Salesforce records, every object was connected to demonstrate how Sales Cloud supports real-world sales organizations.

---

# End-to-End Sales Process

```text
Lead
    ↓
Qualified Lead
    ↓
Account
    ↓
Contact
    ↓
Opportunity
    ↓
Products
    ↓
Price Book
    ↓
Quote
    ↓
Customer Decision
    ↓
Closed Won / Active Sales Pipeline
```

---

# Lead Generation

The project begins with prospective customers entering the sales pipeline through multiple acquisition channels.

Lead sources include:

- Website
- Partner Referral
- Phone Inquiry
- Other Marketing Sources

Leads are evaluated before being converted into customer accounts.

---

# Customer Management

Qualified leads become Salesforce Accounts.

Each account contains:

- Company information
- Industry
- Website
- Phone number
- Customer status
- Related Contacts
- Related Opportunities

Each customer includes one or more Contacts representing key stakeholders.

Examples include:

- Chief Information Officers
- Directors of Information Technology
- Procurement Managers
- Operations Directors

Contact Roles identify decision makers and influencers during the sales process.

---

# Opportunity Management

Each customer progresses through a realistic sales pipeline.

Stages represented include:

- Qualification
- Proposal / Price Quote
- Negotiation / Review
- Closed Won

Each opportunity includes:

- Expected Revenue
- Probability
- Close Date
- Products
- Activities
- Contact Roles
- Stage History
- Related Quotes

---

# Product Management

CloudShield Security sells subscription-based cybersecurity solutions.

Products include:

- Haze Professional
- Haze Enterprise
- Premium Support
- Managed Detection & Response
- Security Awareness Training

Products are associated with Opportunities through Opportunity Products.

---

# Price Books

Different customer segments receive different pricing strategies.

Price Books created:

- Standard
- Healthcare
- Education
- Government

This demonstrates customer-specific pricing and Salesforce Price Book functionality.

---

# Quote Management

Quotes are generated directly from Opportunities.

Each quote contains:

- Quote Line Items
- Product Pricing
- Quantities
- Synchronization with Opportunity
- Proposal Status

The project includes proposals in multiple stages:

- Draft
- Presented
- Accepted

---

# Industries Represented

The simulated customer portfolio includes:

| Industry | Example Customer |
|-----------|------------------|
| Healthcare | CS - Treasure Valley Health System |
| Education | Boise State University |
| Government | Idaho Department of Transportation |
| Manufacturing | Pacific Northwest Manufacturing Group |

---

# Salesforce Objects Used

- Leads
- Accounts
- Contacts
- Opportunities
- Products
- Price Books
- Opportunity Products
- Quotes
- Contact Roles
- Activities
- Reports

---

# Skills Demonstrated

## Salesforce

- Sales Cloud
- CRM Administration
- Opportunity Management
- Quote Management
- Contact Roles
- Product Catalog Management
- Price Books
- Reporting
- Pipeline Management

## Sales

- SaaS Sales
- Account Management
- Customer Success
- Consultative Selling
- Opportunity Forecasting
- Stakeholder Management
- Revenue Management

---

# Project Outcome

This portfolio demonstrates practical experience building and managing a realistic Salesforce Sales Cloud environment that models a complete B2B SaaS sales organization.

The project emphasizes business process understanding in addition to Salesforce platform knowledge, showcasing how customer relationships, products, pricing, opportunities, and quotes work together throughout the sales lifecycle.