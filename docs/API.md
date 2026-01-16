# API Documentation

## Endpoints
### AML Alert Intake
- **Description**: Collect and validate AML alerts from transaction monitoring systems; attach runId and timestamp.
- **Type**: Processing

### Entity Resolution
- **Description**: Resolve customer entities and identify related parties across KYC, CRM, and external data.
- **Type**: Processing

### Transaction Pattern Analysis
- **Description**: Detect structuring, smurfing, and velocity anomalies; emit scored indicators.
- **Type**: Processing

### Risk Scoring
- **Description**: Aggregate indicator scores with profile risk; compute composite SAR likelihood.
- **Type**: Processing

### Investigation Planning
- **Description**: Draft action plan, assign tasks, and set SLAs with decision gates.
- **Type**: Processing

### SAR Report Compilation
- **Description**: Assemble narrative, evidence set, and filing metadata; persist and return JSON.
- **Type**: Processing
