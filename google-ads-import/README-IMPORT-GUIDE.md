# Google Ads Editor — Import Guide

## Files in This Folder

| File | What It Contains |
|---|---|
| `campaigns.csv` | 5 campaigns with budgets and settings |
| `keywords.csv` | 71 keywords across 12 ad groups |
| `ads.csv` | 12 Responsive Search Ads (1 per ad group) |
| `negative-keywords.csv` | 60 negative keywords to block wasted spend |

## Step-by-Step Import

### 1. Download Google Ads Editor
- Go to: https://ads.google.com/intl/en_au/home/tools/ads-editor/
- Download and install (free)

### 2. Sign In
- Open Google Ads Editor
- Sign in with your Google Ads account
- Select your account (Conversion ID: 10906158351)

### 3. Import Campaigns First
- Go to **Account** → **Import** → **Import from CSV**
- Select `campaigns.csv`
- Review and apply

### 4. Import Keywords
- Go to **Account** → **Import** → **Import from CSV**
- Select `keywords.csv`
- Map columns if prompted
- Review and apply

### 5. Import Ads
- Go to **Account** → **Import** → **Import from CSV**
- Select `ads.csv`
- Review and apply

### 6. Import Negative Keywords
- Go to **Account** → **Import** → **Import from CSV**
- Select `negative-keywords.csv`
- Review and apply

### 7. Review Everything
- Check all campaigns show as "Paused"
- Verify keywords, ads, and negatives are in the right ad groups
- Check Final URLs all point to: https://dianapps.com/technology-partner-australia

### 8. Post Changes
- Click **Post** (top toolbar)
- Select all changes → Post
- All 5 campaigns will upload to Google Ads (in Paused state)

### 9. Enable Campaigns
- Go to ads.google.com
- Start with Campaign 1 (StaffAug-AU) and Campaign 2 (AI-Integration-AU)
- Change status from Paused → Enabled
- Launch Campaigns 3-5 in Month 2 and 3 as per the plan

## Campaign Launch Order

| Campaign | Launch When | Daily Budget (AUD) |
|---|---|---|
| StaffAug-AU | Month 1 (now) | $35 |
| AI-Integration-AU | Month 1 (now) | $30 |
| Cybersecurity-AU | Month 2 | $30 |
| Legacy-Modernisation-AU | Month 3 | $25 |
| Healthcare-FHIR-AU | Month 3 | $20 |

## After Launch — Weekly Checklist
- Check search terms report — add negatives for irrelevant queries
- Pause keywords with CPC > AUD $25 and zero conversions after 50 clicks
- Kill ad groups with CPL > 2x target after 7 days
- Double budget on winning ad groups
