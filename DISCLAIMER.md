# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-hubspot-user-permission-offboarding-sanitizer`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-hubspot-user-permission-offboarding-sanitizer`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, orphaned records, workflows, sequences or access this workflow fails to detect, incorrect or incomplete fallback-owner recommendations, lost deals or missed customer commitments, duplicate or missing notifications and tasks, API rate-limit penalties, and decisions made because of a report or the absence of one.

* **No Warranty:** All software, n8n JSON blueprints, JavaScript modules and checklist templates are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. Detection rules, property names, risk scores and priorities are illustrative defaults and are not guaranteed to suit your portal.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, a test Slack channel and a test Todoist project, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live HubSpot, Slack or Todoist credentials. Treat every checklist and fallback-owner suggestion as a draft that a person must review before records are reassigned, sequences are changed or access is removed. The workflow is read-only towards HubSpot and doesn't replace your offboarding process, HubSpot's permission controls or a security review.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA), employment and data-protection obligations, and security policies of HubSpot, Slack, Todoist and any connected services. That includes limiting who can read offboarding reports and n8n executions, processing departing employees' personal data lawfully, keeping credentials out of version control, and reviewing every reassignment and access change made because of a report.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., Doist Inc. (Todoist), or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All people, email addresses, user and owner IDs, teams, deals, tasks, tickets, sequences and workflows in the pinned sample data and documentation are fictional and exist only for testing. Workflow action schemas in the fixtures are simplified. Any resemblance to real people, portals or organisations is coincidental. Placeholder values such as `YOUR_HUBSPOT_PRIVATE_APP_TOKEN`, `YOUR_SLACK_WEBHOOK_URL`, `YOUR_TODOIST_API_TOKEN` and `YOUR_HUBSPOT_PORTAL_ID` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, employment, compliance or security advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
