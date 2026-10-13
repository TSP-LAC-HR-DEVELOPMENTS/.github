# TSP LAC · HR Developments

Welcome to **TSP-LAC-HR-DEVELOPMENTS**, our shared engineering workspace for SAP HR and payroll solutions.

This organization brings together the project template and the repositories used by our consultants to develop, document and maintain solutions. Requirements, specifications, source artifacts and technical evidence belong in each solution's repository, providing a common baseline for the delivery team.

## Start here

**[Open the SAP Development Template](https://github.com/TSP-LAC-HR-DEVELOPMENTS/tsp-sap-development-template)**

> **Current template: v0.11.0-rc.1 — internal acceptance pilot.**
>
> This candidate is limited to synthetic scenarios, simulated approvals and non-production SAP environments. No client delivery or production release is authorized. Independent review of the candidate's governance changes remains pending. These restrictions apply to projects created from this candidate until an explicitly approved release supersedes it.

## Create a solution repository

1. Open the template and select **Use this template → Create a new repository**.
2. Set the owner to **TSP-LAC-HR-DEVELOPMENTS** and select **Private**. Leave **Include all branches** off.
3. Use the agreed solution identity to name the repository:

   ```text
   <CLIENT>_<SOLUTION-ID>_<SHORT-DESCRIPTION>
   ```

   Synthetic pilot example: `DEMO_INT-001_Employee-Replication`.

4. Clone the new repository, open it in VS Code and open your supported AI coding agent.
5. Say **“Start a new project.”** and follow **Your Next Action** in `START-HERE.md`.
6. Coordinate access for the consultants assigned to the solution with the repository owner or an organization owner.

Use **one repository per solution**, shared by its delivery team. Each consultant works in that repository through branches and pull requests. Keep the central template clean so it remains a reusable starting point.

The Technical Lead confirms the client and persistent solution/integration ID during initialization. Refer to the template's [Solution Identity Contract](https://github.com/TSP-LAC-HR-DEVELOPMENTS/tsp-sap-development-template/blob/main/.framework/SOLUTION-IDENTITY-CONTRACT.md) for the naming rules.

## How we work

- **SAP Standard First:** assess standard capabilities before proposing custom development.
- **Specification-driven development:** make requirements and design explicit before implementing.
- **Traceability:** keep specifications, implementation, technical tests and documentation connected.
- **Human approval:** AI may prepare work and evidence; accountable people approve the required decisions.
- **Shared engineering baseline:** preserve the solution repository beyond the initial project for future maintenance and handover to **CloudCare**.

Follow the framework's next action rather than editing its state or generated views manually. Functional testing and UAT are coordinated separately from the development framework's technical testing.

## Teams and access

| Team | Central template access | Purpose |
| --- | --- | --- |
| `framework-consultants` | Read | Use the template and start solution developments |
| `framework-maintainers` | Write | Maintain the shared template and coordinate framework distribution |

Access to each solution repository is assigned separately. Membership in the consultant team does not grant access to every customer's work.

If you cannot open the template, ask an organization owner to check your membership, team assignment and two-factor authentication. If you need access to a solution, contact its repository owner or the delivery lead.

## Documentation and confidentiality

Keep project documentation and technical evidence in the solution repository. To create a Customer Workbook draft, ask the coding agent: **“Generate the customer workbook.”** Review the workbook and its completeness report before any approved publication.

Keep repositories private. Never commit credentials or production HR/payroll personal data, and follow the framework's AI Data Policy. Internal evidence and the workbook publication's `internal/` folder are not customer deliverables. All output from the current acceptance pilot remains internal.

## Framework improvements and feedback

The [framework maintainer repository](https://github.com/TSP-LAC/tsp-sap-development-framework) owns framework development and release preparation. This organization's template distributes the approved starting point, subject to the candidate restrictions above.

Report framework issues to the maintainers with the version, affected stage, expected result, actual result and sanitized evidence. Record solution-specific requirements and defects in the relevant solution repository.

Existing solution repositories do not automatically receive template updates. Coordinate upgrades with the maintainers and preserve each solution's approved identity, specifications, state and evidence.

**New consultant?** Start with the template README, confirm your access and complete a pilot onboarding with your Technical Lead.
