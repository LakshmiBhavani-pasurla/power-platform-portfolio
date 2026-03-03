# Approval Workflow Application

## Problem Statement

Many organizations rely on manual email-based approval processes which lead to delays, lack of tracking, and limited visibility into request status.

This solution digitizes and automates a multi-stage approval process using Power Platform.

---

## Solution Overview

Built a Power Apps Canvas Application integrated with SharePoint Online and Power Automate to automate request submission, approval routing, and status tracking.

---

## Tech Stack

- Power Apps (Canvas)
- Power Automate (Cloud Flows)
- SharePoint Online (List backend)
- Power BI (optional reporting)

---

## Key Features

- Request submission form
- Multi-level approval (Manager → Finance)
- Conditional routing based on request amount
- Real-time status tracking
- Email notifications
- Escalation logic
- Role-based visibility

---

## Architecture Flow

1. User submits request in Power Apps  
2. Item stored in SharePoint List  
3. Power Automate triggers approval workflow  
4. Status updated based on decision  
5. Notification sent to requester  

---

## Screenshots

(Screenshots will be added here)

---

## Sample Data Structure

SharePoint List Columns:

- Title (Single line of text)
- RequestType (Choice)
- Description (Multiple lines)
- Amount (Currency)
- Status (Choice: Submitted / Approved / Rejected)
- ApproverEmail (Person/Group)
- CreatedBy (Person)

---

## Business Impact

- Reduced approval turnaround time by up to 40%
- Improved transparency and tracking
- Eliminated dependency on manual email approvals
