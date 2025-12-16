# Salesforce-lead-product-interest-automation
Salesforce Admin project – Lead follow-up automation using Workflow Rules
# Salesforce Lead Product Interest Automation

## Project Overview
This project demonstrates Salesforce Admin automation using Workflow Rules to improve Lead follow-up efficiency.

## Business Problem
Sales teams were missing timely follow-ups on Leads based on Product Interest.

## Solution
Implemented Salesforce Workflow Rules on the Lead object to automatically create follow-up Tasks.

## Automation Details
- Object: Lead
- Field: Product Interest (Picklist)
- Trigger:
  - Lead is created
  - Product Interest = Software OR Consulting
- Action:
  - Create follow-up Task for Lead Owner
  - Due Date = Same day
  - Status = Not Started

## Tools Used
- Salesforce Workflow Rules
- Lead Object
- Task Automation
- Trailhead Hands-On Org

## Testing
- Created Leads with Product Interest values
- Verified Task creation under Lead Activities

## Outcome
- Improved follow-up consistency
- Reduced manual effort
