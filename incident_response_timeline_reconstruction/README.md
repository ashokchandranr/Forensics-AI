# Incident Response Timeline Reconstruction

Multi-source event stitching, chronology confidence, and blast-radius analytics for active incidents.

## Operational Question

These notebooks focus on which timeline branches to trust, which assets to contain first, and where evidence gaps remain.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| EDR and host telemetry | Process ancestry, persistence, and privilege paths | Sensor dropouts create false gaps |
| Email, identity, and proxy logs | Initial access, token use, and exfiltration path clues | Retention windows differ by control |
| Ticketing and alert streams | Analyst actions, deduplication, and case timing | Manual annotations can be delayed |
| Backup and recovery metadata | Blast radius and restoration feasibility | Backup jobs produce large but benign activity |

## Notebook Catalog

1. **[01_event_log_temporal_sequencing.ipynb](01_event_log_temporal_sequencing.ipynb)**: Use AI/ML to make event log temporal sequencing more auditable, faster, and easier to operationalize.
1. **[02_attack_path_stage_classification.ipynb](02_attack_path_stage_classification.ipynb)**: Use AI/ML to make attack path stage classification more auditable, faster, and easier to operationalize.
1. **[03_host_process_tree_anomaly_scoring.ipynb](03_host_process_tree_anomaly_scoring.ipynb)**: Use AI/ML to make host process tree anomaly scoring more auditable, faster, and easier to operationalize.
1. **[04_email_to_endpoint_incident_correlation.ipynb](04_email_to_endpoint_incident_correlation.ipynb)**: Use AI/ML to make email to endpoint incident correlation more auditable, faster, and easier to operationalize.
1. **[05_case_timeline_gap_detection.ipynb](05_case_timeline_gap_detection.ipynb)**: Use AI/ML to make case timeline gap detection more auditable, faster, and easier to operationalize.
1. **[06_ransomware_blast_radius_estimation.ipynb](06_ransomware_blast_radius_estimation.ipynb)**: Use AI/ML to make ransomware blast radius estimation more auditable, faster, and easier to operationalize.
1. **[07_identity_compromise_reconstruction.ipynb](07_identity_compromise_reconstruction.ipynb)**: Use AI/ML to make identity compromise reconstruction more auditable, faster, and easier to operationalize.
1. **[08_alert_deduplication_priority.ipynb](08_alert_deduplication_priority.ipynb)**: Use AI/ML to make alert deduplication priority more auditable, faster, and easier to operationalize.
1. **[09_log_source_reliability_scoring.ipynb](09_log_source_reliability_scoring.ipynb)**: Use AI/ML to make log source reliability scoring more auditable, faster, and easier to operationalize.
1. **[10_incident_containment_playbook_ranking.ipynb](10_incident_containment_playbook_ranking.ipynb)**: Use AI/ML to make incident containment playbook ranking more auditable, faster, and easier to operationalize.

## Standards and References

- NIST SP 800-61
- Diamond Model of Intrusion Analysis
- SANS incident timeline reconstruction practices
