| Title / Action                                   | Capability / Swimlane | Phase | Owner | Dependencies (optional) |
|--------------–-----------------------------------|-----------------------|-------|-------|-------------------------|
| Set up SAP Cloud Identity Services (IAS + IPS) | Security & Identity | Build Foundation | Security Lead | Corporate IdP details |
| Configure SSO for Fiori Launchpad | Security & Identity | Build Foundation | Security Lead | WP-SEC-01 |
| ... | ... | ... | ... | ... |





## Security & Identity

Action:
 - Complete the rollout of SAP Cloud Identity Services (IAS + IPS) integration for the remaining SAP components that are not yet covered. 

description:
- Complete the rollout of SAP Cloud Identity Services (IAS + IPS) integration for the remaining SAP components that are not yet covered. Reuse the existing configuration patterns, trust setups, and provisioning jobs already established for the currently integrated components.

action:
- Integrate Saviynt with SAP Cloud Identity Services (IAS + IPS)

description:
- Establish bidirectional integration between Saviynt and SAP Cloud Identity Services. Configure Identity Provisioning (IPS) jobs and/or SCIM connectors so that user lifecycle events (create, update, disable) and access assignments flow between Saviynt (as the governance system of record) and SAP Cloud Identity Services. 

action:
- Align SAP Cloud Identity Services with Achmea ESA recommendations to achieve compliance

description:
Review and implement the Achmea Enterprise Security Architecture (ESA) recommendations specifically applicable to SAP Cloud Identity Services (IAS + IPS)


- Set up fine-grained authorization for SAP Cloud Identity Services using Authorization Policies
- Define and implement signing certificate renewal procedure for SAP Cloud Identity Services aligned with Achmea security policies
- Set up run organization and support procedures for SAP Cloud Identity Services

