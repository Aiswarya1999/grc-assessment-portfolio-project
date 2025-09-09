# GRC Portfolio Project — FinBank Ltd

This folder includes templates and example content for a simulated risk & compliance assessment for a fictitious company where I assessed risks, checked compliance, and prepared audit-ready documents

## Scenario
Industry: Financial Services (UK-based fintech handling payment data)
Size: ~200 employees, cloud-first (AWS/Azure), customer portal + mobile app
Regulatory Scope: GDPR + PCI DSS + ISO/IEC 27001
Assessment Date: 2025-09-09

## Files
- **Risk_Register.xlsx** — master risk register (with sample risks and scoring). If Excel wasn't available, see CSV fallback.
- **Compliance_Checklists.xlsx** — ISO 27001, GDPR, PCI DSS checklists in separate tabs (place evidence, status, gaps, actions). If Excel wasn't available, see CSV fallbacks.
- **Internal_Audit_Checklist.xlsx** — audit template with example findings (fallback CSV included if needed).
- **Risk_Assessment_Report.docx** — management-friendly report (Markdown fallback provided if DOCX couldn't be generated).
- **Management_Summary.pptx** — slides for executives, plus **Risk_Heat_Map.png** for visuals (Markdown fallback provided if PPTX couldn't be generated).

## How to Use (Step-by-Step)
1. **Define/Refine Scope**: Update the scenario (industry, systems, data flows, regulations) to match your target company profile.
2. **Populate Risk Register**: Add assets, threats, vulnerabilities; set impact and likelihood (1–5). The sheet auto-calculates the Risk Score and category.
3. **Plan Treatments**: For each High/Medium risk, add recommended actions, owners, and target dates.
4. **Fill Compliance Checklists**: For each control/requirement, record evidence, status (✅/⚠️/❌), gaps, and actions.
5. **Run an Internal Audit**: Use the audit template to review key controls; document findings, severity, and management responses.
6. **Update the Report**: Edit the DOCX report to reflect your organization, findings, and treatment plan.
7. **Update the Slides**: Refresh the top risks and roadmap in the PPT; replace the heat map if your scoring changes.
8. **Publish**: Commit these files to your GitHub portfolio (with a short README) and share on LinkedIn with a brief case-study post.

## Tips
- Keep evidence screenshots/logs in a separate `/evidence` subfolder (avoid real PII; use anonymized or synthetic data).
- Map risks/controls to business objectives to demonstrate consulting impact.
- Add KPIs (e.g., MFA coverage %, time-to-close High risks) to show progress over time.

Good luck and have fun building your GRC portfolio!
