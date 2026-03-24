# Cloud Infrastructure Audit Forensics

Identity, audit, and control-plane analytics for cloud compromise, drift, and storage misuse.

## Operational Question

These notebooks focus on whether to suspend credentials, snapshot workloads, or review trust relationships and storage exposure.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| CloudTrail / audit logs | API bursts, impossible sequences, and account misuse | Organization-level aggregation can delay context |
| Identity and access metadata | Role chaining, policy drift, and dormant privilege activation | Break-glass workflows look unusual by design |
| Storage and object access logs | Exfiltration volume, geographic spread, and retrieval anomalies | Lifecycle jobs can create benign spikes |
| Kubernetes and serverless events | Ephemeral execution changes and secrets access | Autoscaling can mimic attack bursts |

## Notebook Catalog

1. **[01_aws_cloudtrail_anomaly_detection.ipynb](01_aws_cloudtrail_anomaly_detection.ipynb)**: Use AI/ML to make aws cloudtrail anomaly detection more auditable, faster, and easier to operationalize.
1. **[02_privilege_escalation_path_scoring.ipynb](02_privilege_escalation_path_scoring.ipynb)**: Use AI/ML to make privilege escalation path scoring more auditable, faster, and easier to operationalize.
1. **[03_storage_exfiltration_pattern_detection.ipynb](03_storage_exfiltration_pattern_detection.ipynb)**: Use AI/ML to make storage exfiltration pattern detection more auditable, faster, and easier to operationalize.
1. **[04_console_login_impossible_travel.ipynb](04_console_login_impossible_travel.ipynb)**: Use AI/ML to make console login impossible travel more auditable, faster, and easier to operationalize.
1. **[05_service_principal_abuse_detection.ipynb](05_service_principal_abuse_detection.ipynb)**: Use AI/ML to make service principal abuse detection more auditable, faster, and easier to operationalize.
1. **[06_infrastructure_drift_tampering_classification.ipynb](06_infrastructure_drift_tampering_classification.ipynb)**: Use AI/ML to make infrastructure drift tampering classification more auditable, faster, and easier to operationalize.
1. **[07_kubernetes_audit_log_intrusion_detection.ipynb](07_kubernetes_audit_log_intrusion_detection.ipynb)**: Use AI/ML to make kubernetes audit log intrusion detection more auditable, faster, and easier to operationalize.
1. **[08_cross_account_trust_risk_scoring.ipynb](08_cross_account_trust_risk_scoring.ipynb)**: Use AI/ML to make cross account trust risk scoring more auditable, faster, and easier to operationalize.
1. **[09_serverless_execution_abuse_detection.ipynb](09_serverless_execution_abuse_detection.ipynb)**: Use AI/ML to make serverless execution abuse detection more auditable, faster, and easier to operationalize.
1. **[10_secrets_access_anomaly_triage.ipynb](10_secrets_access_anomaly_triage.ipynb)**: Use AI/ML to make secrets access anomaly triage more auditable, faster, and easier to operationalize.

## Standards and References

- AWS CloudTrail user guide
- MITRE ATT&CK for Cloud
- NIST SP 800-61
