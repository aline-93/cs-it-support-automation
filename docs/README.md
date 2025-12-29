# Documentation

Detailed explanation of the automation workflow and process logic.
# Automation Workflow Documentation

This document explains the logic, structure, and purpose of the Customer Support & IT automation workflow demonstrated in this repository.

---

## 1. Problem Statement

In daily Customer Support and IT activities, tracking work manually can lead to:
- Loss of visibility of support efforts
- Inconsistent task logging
- Difficulty demonstrating workload to management
- Inefficient follow-up on requests

The goal of this workflow was to create a **simple, reliable and transparent process** to log support activities without adding operational overhead.

---

## 2. Solution Overview

The solution uses Microsoft Power Automate combined with Microsoft Forms and Planner to:

- Capture support-related activities through a structured internal form
- Automatically create tasks for tracking and accountability
- Centralize support activity visibility
- Reduce manual tracking and human error

This approach prioritizes **process clarity over technical complexity**.

---

## 3. Workflow Logic

### Step 1: Form Submission
An internal Microsoft Form is filled after a support interaction.
The form includes:
- Type of request (checkboxes)
- Description of the activity
- Urgency or priority
- Responsible area (CS / IT / Support)

---

### Step 2: Power Automate Trigger
The form submission triggers a Power Automate flow that:
- Validates the input
- Applies conditional logic based on request type
- Routes the data to the appropriate destination

---

### Step 3: Task Creation
Based on the submitted data, the flow:
- Creates a task in Microsoft Planner
- Assigns labels or categories
- Adds context in the task description

This ensures each activity is traceable and reviewable.

---

## 4. ITSM-Oriented Mindset

Although this is a lightweight
