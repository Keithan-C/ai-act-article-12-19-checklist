# EU AI Act — Article 12 & 19 Compliance Checklist
For Automotive OTA and ADAS Teams | August 2026 Deadline

## ARTICLE 12 — LOGGING CAPABILITY

### Logging Architecture
[ ] Automatic logging enabled (no manual trigger required)
[ ] Logging active during all operational use
[ ] OTA deployment events captured with timestamp
[ ] Infrastructure configured to capture AI-specific log fields

### Data Captured Per AI System
[ ] Model inputs logged (sensor data, environmental conditions)
[ ] Model outputs logged (decisions, recommendations, scores)
[ ] Confidence/uncertainty values captured
[ ] Human override and intervention events logged
[ ] System failure and fallback events logged
[ ] Version identifier of deployed model captured in each log entry

### Logging Schema
[ ] Defined schema exists per high-risk AI system
[ ] Schema maps each field to Article 12 requirement
[ ] Schema reviewed and approved by compliance team
[ ] Schema version-controlled alongside model versions

### Retrieval
[ ] Logs retrievable within 48 hours of regulator request
[ ] Export format documented and tested
[ ] Retrieval procedure written and assigned to owner

## ARTICLE 19 — LOG CONTROL

### Retention Policy
[ ] Minimum retention period defined and documented
[ ] Retention period reviewed against national authority guidance
[ ] Archival process automated (not manual)
[ ] Deletion procedure documented with approval process

### Access Control
[ ] Log access restricted by role (not open to all staff)
[ ] Access list reviewed and approved
[ ] Access audit trail enabled (who accessed, when, what)
[ ] Quarterly access review scheduled

### Integrity Protection  
[ ] Logs technically protected against deletion or modification
[ ] Integrity verification mechanism in place (hash/signature)
[ ] Tampering detection alerts configured
[ ] Integrity approach documented for audit evidence

## AUDIT READINESS

### Documentation
[ ] Audit Defense Brief exists for each high-risk system
[ ] Brief explains logging compliance in non-technical language
[ ] Brief reviewed by legal team
[ ] Infrastructure Implementation Spec completed

### Team Readiness
[ ] ADAS engineers can explain logging approach without preparation
[ ] Designated compliance spokesperson identified per system
[ ] Mock audit conducted in last 6 months
[ ] Gap remediation plan documented and dated

## STATUS SUMMARY
Last reviewed: [17.02.26]
Reviewed by: [Keithan, LXD Advisory]
Overall status: [] Green [ ] Amber [ ] Red

