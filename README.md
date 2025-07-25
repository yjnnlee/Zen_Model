# Zen_Model

# ICAC Investigation Knowledge Graph

This project models a fictional ICAC (Internet Crimes Against Children) case using ontologies from UCO, CASE, and a custom ICAC namespace. The model represents the lifecycle of a child exploitation report—from hotline intake to a digital forensics investigation and technical findings.

# Scenario Overview

The investigation follows these phases:

1. Report Intake – A suspicious report is received by a hotline agent.
2. ICAC Launches Investigation – The report leads to a formal ICAC investigation.
3. Undercover Operation Plan – A multi-phase undercover operation is planned.
4. Digital Forensics Analysis – Evidence is collected and analyzed using forensic tools.
5. Technical Findings – A final report summarizes key digital evidence.

# Project Structure

Each .ttl file corresponds to a specific phase of the case:

report.ttl : Models the initial hotline report, including agent and timestamps 
investigation.ttl : Links the report to an official ICAC investigation 
undercover_plan.ttl`: Defines a 3-phase undercover task force plan 
forensics.ttl : Describes forensic tools and digital artifacts analyzed 
findings.ttl : Summarizes technical findings from forensic analysis 
