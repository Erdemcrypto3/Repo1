# Dynamics 365 CRM Integration Notes

## Lead Capture Strategy

### Requirements
- Capture leads from multiple microsites
- Automatically create leads in Dynamics CRM
- Track source/campaign information
- Send confirmation emails

### Integration Options

#### Option 1: Power Automate (Recommended)
- HTTP webhook receives form data
- Creates lead in Dynamics
- Sends notifications
- No authentication complexity

#### Option 2: Direct Web API
- JavaScript calls Dynamics Web API
- More control
- Requires OAuth authentication

#### Option 3: Power Pages
- Microsoft-hosted sites
- Built-in Dynamics integration
- Easiest for non-developers

## Lead Fields to Capture
- First Name
- Last Name
- Email
- Phone
- Company
- Campaign Source
- Message/Notes

---
Last Updated: 08/Feb/2026.
