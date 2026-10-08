# DIGITEK AI SUPPORT COPILOT

### AI-Powered Customer Support Triage & Human-in-the-Loop Automation

> **Automate the repetitive. Escalate the risky. Keep humans in control.**

Built for the **Digitek AI Implementation & Automation Intern Assessment**.

---

## 🚀 PROJECT OVERVIEW

The **Digitek AI Support Copilot** is an AI-powered customer support automation that receives customer emails, classifies requests, extracts important information, detects urgency, logs cases, and routes requests to the appropriate response path.

Cases requiring live information, human judgement, or additional verification are escalated instead of allowing the AI to guess.

---

# 🧠 PART 1 — AI SUPPORT AUTOMATION

### Workflow

```text
Gmail
   ↓
Email Processing
   ↓
AI Support Brain
   ↓
Human Review Check
   ↓
Category Router
   ↓
Google Sheets
   ↓
Customer Response
```

### Key Features

- AI customer request classification
- Customer and order information extraction
- Product identification
- Urgency detection
- AI confidence assessment
- Human-review escalation
- Automated Google Sheets logging
- Category-based response routing
- Spam detection
- Suggested response generation

### Support Categories

1. Order status
2. Return/Refund
3. Product question
4. Bulk order
5. Complaint
6. Spam

### Testing

The workflow was tested using six customer scenarios covering:

**Order Status • Return/Refund • Bulk Order • Product Question • Spam • Complaint**

---

# 🛡️ HUMAN-IN-THE-LOOP DESIGN

The automation does not blindly answer every customer request.

Cases requiring human judgement or unavailable information are escalated for review.

Examples include:

- Live order or tracking information
- Refund or replacement decisions
- Product compatibility
- Bulk pricing or stock
- Low-confidence AI outputs
- Missing information
- Escalated complaints

> **AI prepares the case. Humans make the decisions.**

---

# 📊 GOOGLE SHEETS SUPPORT HUB

Every processed case is logged with:

- Timestamp
- Customer name
- Phone
- Customer email
- Order number
- Category
- Product
- Urgency
- Summary
- AI confidence
- Human review status
- Review reason
- Suggested reply
- Status
- Original message

The **AI Control Center** provides a dashboard for viewing support activity, categories, urgency, spam, and human-review requirements.

---

# 🎨 PART 2 — DIGITEK REFUND FLOW

## AI-Powered Returns & Refund Automation

Part 2 focuses on improving the **returns and refunds process** using a human-in-the-loop automation model.

### Current Process

```text
Customer Request
      ↓
Read Email
      ↓
Identify Order
      ↓
Understand Issue
      ↓
Check Information
      ↓
Decide Next Action
      ↓
Respond
```

### Proposed Process

```text
Customer Email
      ↓
AI Triage
      ↓
Extract & Summarize
      ↓
Risk / Confidence Check
      ↓
Human Review
      ↓
Refund / Replacement Decision
```

### What Is Automated

- Email triage
- Request classification
- Customer information extraction
- Order information extraction
- Product identification
- Urgency detection
- Case summarization
- AI confidence assessment
- Case logging
- Suggested responses
- Category routing

### What Remains Human

- Refund eligibility decisions
- Replacement decisions
- Live order or refund status
- Unclear requests
- Escalated complaints
- Product compatibility when information is unavailable
- Bulk pricing or stock decisions
- Low-confidence cases

---

# ⚙️ TOOLS USED

| Tool | Purpose |
|---|---|
| **n8n** | Workflow automation and routing |
| **Google Gemini** | AI classification and information extraction |
| **Gmail** | Customer email intake and responses |
| **Google Sheets** | Support case logging and dashboard |
| **Canva** | Part 2 presentation design |

---

# 📈 BENEFITS

The proposed automation is designed to:

- Reduce repetitive support work
- Speed up initial case triage
- Standardize information extraction
- Improve case organization
- Identify urgent requests
- Route complex cases to humans
- Reduce unsupported AI decisions
- Give support teams a structured view of incoming requests

### Illustrative Efficiency Model

```text
Manual Support
~5 min / case

Read → Classify → Extract → Log → Acknowledge
```

```text
AI-Assisted Support
~1 min / case

Triage → Extract → Log → Escalate
```

### ≈80% LESS REPETITIVE HANDLING TIME

At an illustrative volume of 100 cases/day:

**8.3 hrs manual → 1.7 hrs AI-assisted**

**≈6.7 hrs/day potential saving**

> *Illustrative estimate for assessment purposes, not a measured production result.*

---

# 🛡️ AUTOMATION WITH GUARDRAILS

The system follows four principles:

### 01 — LIVE DATA

If tracking or refund status requires unavailable information:

**→ Human Review**

### 02 — AI UNCERTAINTY

If information is missing or AI confidence is low:

**→ Human Review**

### 03 — HIGH-RISK REQUESTS

Refunds, replacements, complaints, and unusual cases can require:

**→ Human Judgement**

### 04 — NO GUESSING

The AI should not invent:

- Pricing
- Stock availability
- Compatibility
- Delivery status
- Refund status

> **Automate the repetitive. Escalate the risky. Keep humans in control.**

---

# 🎥 DEMO

### Digitek AI Support Copilot — Part 1 Demo

The demonstration covers:

- Gmail customer email intake
- AI classification
- Customer information extraction
- Urgency and confidence detection
- Human-review routing
- Category-based routing
- Google Sheets case logging
- AI Control Center dashboard

### ▶ Watch the Demo

**[Open Demo Recording](PASTE-YOUR-GOOGLE-DRIVE-LINK-HERE)**

---

# 📁 REPOSITORY STRUCTURE

```text
DIGITEK AI SUPPORT COPILOT
│
├── README.md
│
├── 01_PART_1_AI_SUPPORT_AUTOMATION
│   ├── 01_WORKFLOW
│   │   └── digitek_ai_support_copilot.json
│   │
│   ├── 02_SCREENSHOTS
│   │   ├── 01_Gmail_Trigger.png
│   │   ├── 02_Clean_Email_Output.png
│   │   ├── 03_AI_Brain_and_Output.png
│   │   ├── 04_Human_Review_Branch.png
│   │   ├── 05_Category_Router.png
│   │   ├── 06_Google_Sheet_Results.png
│   │   ├── 07_AI_Control_Center.png
│   │   └── 08_COMPLETE_WORKFLOW.png
│   │
│   ├── 03_TEST_EMAILS
│   │   └── six_test_emails.txt
│   │
│   └── 04_DOCUMENTATION
│       └── part_1_notes.pdf
│
├── 02_PART_2_REFUND_AUTOMATION
│   ├── DIGITEK_REFUND_FLOW.pdf
│   └── DIGITEK_REFUND_FLOW.pptx
│
└── 03_DEMO
```

---

# 🔐 SECURITY & PRIVACY

The repository should not contain:

- Passwords
- API keys
- OAuth tokens
- Private credentials
- Sensitive customer information

Credentials remain configured within the connected tools rather than being exposed in the project documentation.

The repository is intended to remain **private unless public access is specifically requested by Digitek**.

---

# 🎯 PROJECT OUTCOME

The completed solution demonstrates how AI and workflow automation can reduce repetitive customer-support work while keeping humans in control of important decisions.

The system combines:

**Email Intake → AI Understanding → Data Extraction → Classification → Human Escalation → Case Logging → Customer Response**

This creates a support workflow that is:

- Faster
- More structured
- Easier to monitor
- Safer for high-risk cases
- Designed around human-in-the-loop decision making

---

# 👩‍💻 PROJECT INFORMATION

**Assessment:** Digitek AI Implementation & Automation Intern Assessment

**Project:** Digitek AI Support Copilot

**Part 1:** AI Customer Support Automation

**Part 2:** AI-Powered Returns & Refund Automation

**Focus:** AI Automation • Customer Support • Human-in-the-Loop • Workflow Automation

---

## ⭐ FINAL PRINCIPLE

> **AI prepares the case. Humans make the decisions.**
   ↓
Category Router
   ↓
Google Sheets
   ↓
Customer Response
