# ITSM Incident Lite – ServiceNow

A production-style Incident Management implementation built on ServiceNow,
demonstrating priority calculation, auto-assignment, SLAs, record producers,
performance analytics, and automated testing.

## Project Objective
To design a real-world Incident Management flow aligned with ITIL best practices
and demonstrate hands-on ServiceNow development using Update Sets and GitHub.

## Features Implemented
- Priority calculation using Impact & Urgency
- Automatic assignment using custom routing tables
- On-call rotation logic
- Record Producer for incident creation via Service Portal
- Response and Resolution SLAs with pause on Hold
- Flow Designer notifications for high priority incidents
- Performance Analytics dashboard
- Automated Test Framework (ATF) coverage

## Technical Components
- Script Includes
- Business Rules
- Client Scripts
- UI Policies
- Custom Tables
- Record Producers
- SLAs
- Flow Designer
- Performance Analytics
- ATF

## Installation
1. Import the update set from `/update_sets/P01_Incident_Lite.xml`
2. Preview and commit the update set
3. Ensure ITSM, SLA, PA, and Flow Designer plugins are active
4. Run PA data collection if required

## Demo Flow
1. User submits incident via Record Producer
2. Priority calculated automatically
3. Assignment group and assignee populated
4. SLAs attached and managed
5. Dashboards reflect incident metrics

## Notes
- Built without Studio source control
- Uses Update Set–based deployment (enterprise standard)
