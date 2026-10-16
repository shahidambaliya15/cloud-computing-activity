# Cloud Computing Activities — Project Report

## Project overview
**Project:** CloudLab — Cloud Computing Activities  
**Implementation:** HTML, CSS, and JavaScript in one static webpage  
**Purpose:** Demonstrate key cloud-computing concepts through a responsive, interactive learning page.

## Objectives
- Review a basic cloud deployment process.
- Understand virtual-machine resource sizing.
- Identify common cloud security controls.
- Document operational risks and service-level agreement (SLA) topics.
- Explore workload utilization and auto-scaling concepts.

## Activity 1 — Cloud service deployment checklist
The page presents common deployment-planning steps: requirements, service model selection (IaaS/PaaS/SaaS), region and availability planning, identity/access configuration, monitoring, backups, and recovery targets. Users can tick items and see completion progress.

## Activity 2 — Virtual machine sizing simulator
Interactive sliders allow the user to adjust vCPU, memory, and storage. The page displays the selected configuration and a simple guidance message for a small, moderate, or larger workload.

## Activity 3 — Cloud security review
A checklist covers multi-factor authentication, least-privilege access, encryption, logging/alerting, and backup testing. The page counts checked controls and displays a brief status message.

## Activity 4 — Risk and SLA framework
A sample risk register lists service outage, data loss, unauthorized access, and unexpected cost, alongside mitigations and responsible roles. SLA discussion points include availability targets, measurement periods, support response, exclusions, and service credits.

## Activity 5 — Performance and auto-scaling simulator
Users adjust a sample workload percentage and instance count. The page calculates illustrative utilization as load divided by instance count, capped at 100%, and includes a button that recommends an instance count. This is a teaching model, not a real cloud metric.

## Technologies used
- **HTML5:** page structure and controls
- **CSS3:** responsive layout and visual styling
- **JavaScript:** interactive checklists and simulators

## Result
A single-page, responsive learning website was created to demonstrate five introductory cloud-computing activities. It runs locally in a modern browser without external libraries or a build step.

## Conclusion
The project introduces cloud deployment planning, virtualization, security, risk/SLA management, and scaling. In real deployments, configurations and metrics must be validated against the selected cloud provider and application workload.

## Limitation
No cloud resources are created, billed, or managed by this static demonstration.