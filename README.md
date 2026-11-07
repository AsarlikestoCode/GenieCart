AI-Powered Procurement Assistant for Small and Medium Organizations

GenieCart helps organizations reduce purchasing costs by identifying alternative products with comparable or better quality at equal or lower prices. GenieCart recommends products, but humans remain accountable for all procurement decisions.

## Overview

GenieCart demonstrates:

- Input from the world (product requests and procurement constraints)
- AI-assisted recommendation and reasoning
- Business-rule enforcement
- Human-in-the-loop (HITL) approval
- Governance controls
- Organizational memory
- Audit logging and observability

## Features
### Product Recommendation Engine

Given a requested product, GenieCart:

  -Searches available products
  -Compares alternatives
  -Uses an AI model to generate recommendation rationale
  -Estimates savings
  -Presents evidence supporting the recommendation
  -Governance Controls
  -Human approval required
  -Approval authority tiers
  -Vendor restrictions
  -Fund and budget controls
  -Audit trail
  -AI usage monitoring
  -AI self-approval prevention
  -Organizational Memory

GenieCart stores:

- Previous approvals
- Previous rejections
- Vendor history
- Savings achieved
- Procurement decisions

## Quick Start
### Prerequisites
Browser Version

No installation required.

Tested with:

- Microsoft Edge
- Google Chrome
- Mozilla Firefox

Demo Script (3 Minutes)

The following script demonstrates the primary use case end-to-end.

Step 1: Generate Recommendations

Enter:

Plain Text
Product: wireless mouse
Quantity: 10
Budget: 300
Fund: General Operations

Select:

Plain Text
Generate Recommendations

Expected Result:

GenieCart evaluates alternatives
AI generates recommendation rationale
Savings estimate is displayed
Confidence score is displayed

This demonstrates:

Plain Text
Input from the world
↓
AI recommendation
↓
Business output
Step 2: Review Recommendation

Observe:

Recommended product
Current product
Cost comparison
Quality comparison
Evidence section
Confidence score

Expected Result:

A procurement report suitable for business decision making.

Step 3: Human Approval (HITL)

Enter:

Plain Text
Reviewer:
Jordan Lee
 
Role:
Purchasing Manager

Select:

Plain Text
Approve

Expected Result:

Plain Text
Recommendation approved

The decision is stored in Organizational Memory.

Step 4: Organizational Memory

Navigate to:

Plain Text
Procurement Memory

Search:

Plain Text
Jordan

Expected Result:

The approved recommendation appears in memory results.

Step 5: Export Business Evidence

Select:

Plain Text
Export Evidence CSV

Expected Result:

A CSV containing:

Product selected
Savings estimate
Approver
Approval date
AI rationale

This represents business evidence suitable for audit review.

Step 6: Demonstrate Governance Failure

Select:

Plain Text
Simulate AI approving its own recommendation

Expected Result:

Plain Text
ADR-3/4 blocked:
Only an identified human can approve or reject

This demonstrates the Human-In-The-Loop governance requirement.
