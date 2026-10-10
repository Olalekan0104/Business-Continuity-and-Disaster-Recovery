# Coastal Union Bank: Business Continuity and Disaster Recovery

This project develops a proposed Business Continuity and Disaster Recovery (BC/DR) program for Coastal Union Bank, a regional bank with 40 branches and a centralized primary data center. The assessment covers Business Impact Analysis, recovery objectives, crisis communications, crisis management responsibilities, and a tabletop exercise for a major data center outage.

## Table of Contents

- [Project Overview](#project-overview)
- [Network Topology](#network-topology)
- [Tools and Technologies](#tools-and-technologies)
- [Configuration Steps](#configuration-steps)
- [Results and Findings](#results-and-findings)
- [Author](#author)

## Project Overview

Coastal Union Bank has approximately 1,200 employees across 40 branches. Its operations depend on core banking systems, real-time payments, ATMs, mobile and online banking, third-party payment processors, and a primary data center.

The bank has expanded through acquisitions but lacks a unified, tested BC/DR program. Recovery procedures vary across branches, recovery objectives have not been formally established through a documented Business Impact Analysis, and the bank has not conducted joint recovery exercises.

The objectives of this project were to:

- Conduct a Business Impact Analysis for critical banking functions.
- Define Recovery Time Objectives (RTOs), Recovery Point Objectives (RPOs), and Maximum Tolerable Downtime (MTD).
- Establish a crisis declaration and escalation process.
- Develop a customer crisis communication message.
- Design a tabletop exercise involving a primary data center outage and two escalation injects.
- Recommend governance, testing, and continuous improvement activities.

## Network Topology

The scenario describes a centralized banking environment with branch operations, digital banking channels, payment processing, and a primary data center.

```text
                 Coastal Union Bank
                         |
          +--------------+--------------+
          |              |              |
       40 Branches   Digital Banking   ATM Network
          |              |              |
          +--------------+--------------+
                         |
                 Core Banking System
                         |
                  Primary Data Center
                         |
             +-----------+-----------+
             |                       |
      Payment Processing      Third-Party Processor
```

This is a conceptual representation based on the scenario, not a verified network diagram. The assignment does not specify IP addresses, subnet configurations, detailed network connections, or the exact architecture of the recovery site.

## Tools and Technologies

- **Business Impact Analysis (BIA):** Identifies critical functions and evaluates disruption impacts.
- **Recovery Time Objective (RTO):** Defines the target time for restoring a service.
- **Recovery Point Objective (RPO):** Defines the maximum targeted amount of data loss measured in time.
- **Maximum Tolerable Downtime (MTD):** Defines how long a disruption can continue before its impact becomes unacceptable.
- **ISO 22301:** Reference standard for business continuity management systems.
- **Backup and Recovery:** Supports data restoration and disaster recovery testing.
- **Alternate Recovery Site:** Provides an alternative environment for restoring critical services.
- **Crisis Communication Plan:** Defines how customers, employees, and stakeholders receive approved updates.
- **Tabletop Exercise:** Tests crisis decisions, roles, escalation, and recovery coordination.
- **Microsoft Word and PDF:** Used to prepare and document the assessment.
- **GitHub:** Used to publish the project documentation.

The source scenario does not identify specific backup software, disaster recovery platforms, or network security products.

## Configuration Steps

1. **Review the business scenario.** Identified the bank's critical services, infrastructure dependencies, and existing BC/DR governance gaps.

2. **Conduct the Business Impact Analysis.** Reviewed Core Banking, Payments, Branch Operations, and the Primary Data Center as a supporting technology dependency.

3. **Define recovery metrics.** Documented the submitted RTO, RPO, and MTD values and identified targets requiring further business-owner validation.

4. **Design the crisis activation path.** Defined how incidents are escalated, who activates the Crisis Management Team, and how recovery and communication responsibilities are coordinated.

5. **Prepare a customer communication message.** Drafted an outage notification explaining the service disruption, the bank's response, and where customers can obtain updates.

6. **Design the tabletop exercise.** Developed a primary data center fire scenario with two escalation injects involving a failed backup and growing payment disruption.

7. **Define expected response actions.** Included crisis activation, recovery-site assessment, transaction reconciliation, stakeholder communications, and service restoration approval.

8. **Document findings and recommendations.** Identified governance, recovery testing, alternate-site readiness, and communication improvements.

## Results and Findings

The assessment identified several areas requiring improvement.

### Key Findings

- **No unified BC/DR governance:** The bank needs an executive sponsor, documented policy, and defined program ownership.
- **Untested recovery plans:** Recovery capabilities must be demonstrated through exercises and restoration evidence.
- **Unvalidated recovery objectives:** RTO, RPO, and MTD targets require approval from business owners and technology teams.
- **Data center dependency:** The primary data center supports several critical services, creating a significant concentration risk.
- **Crisis communication gaps:** The bank needs approved communication templates, escalation responsibilities, and alternate communication channels.

### Recommended Improvements

- Establish a formal BC/DR policy and governance structure.
- Validate critical functions, dependencies, and recovery objectives through a documented BIA.
- Test backups, restoration, alternate-site readiness, and failover procedures.
- Conduct tabletop exercises involving IT, Operations, Risk, Legal, Communications, and business leadership.
- Develop procedures for transaction reconciliation and customer communication during outages.
- Track corrective actions and repeat tests to demonstrate continued readiness.

The assessment preserves the recovery targets in the submitted assignment while highlighting areas requiring validation. The additional impact estimates are illustrative planning assumptions rather than measured financial losses.

## Author

- **Project:** Coastal Union Bank Business Continuity and Disaster Recovery Assessment
- **Specialization:** Governance, Risk, and Compliance (GRC)
- **Focus Areas:** Business Impact Analysis, RTO, RPO, MTD, Crisis Communications, Disaster Recovery, and Tabletop Testing
