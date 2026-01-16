# Architecture Documentation

## Overview
This Multi-Agent implements Anti-Money Laundering Investigation for Banking & Finance use cases.

## Components
1. **AML Alert Intake**: Collect and validate AML alerts from transaction monitoring systems; attach runId and timestamp.
2. **Entity Resolution**: Resolve customer entities and identify related parties across KYC, CRM, and external data.
3. **Transaction Pattern Analysis**: Detect structuring, smurfing, and velocity anomalies; emit scored indicators.
4. **Risk Scoring**: Aggregate indicator scores with profile risk; compute composite SAR likelihood.
5. **Investigation Planning**: Draft action plan, assign tasks, and set SLAs with decision gates.
6. **SAR Report Compilation**: Assemble narrative, evidence set, and filing metadata; persist and return JSON.

## Data Flow
- Input: AML Alert Intake
- Processing: 6 sequential steps
- Output: SAR Report Compilation
