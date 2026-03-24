# Mobile Device & App Forensics

Call, app, geospatial, and device-state analytics for mobile-centric investigations.

## Operational Question

These notebooks focus on whether to preserve additional device snapshots, subpoena provider data, or expand app-level parsing.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| Call detail records | Burst calling, SIM changes, and contact pivoting | Carrier rounding can blur exact durations |
| Location and sensor traces | Travel plausibility, spoofing, and co-travel analysis | Indoor positioning introduces natural drift |
| App databases and backups | Message, token, and sharing behavior | App version changes alter schema |
| Device health and state logs | Unlocks, battery, and network transitions | Background processes can mimic user activity |

## Notebook Catalog

1. **[01_call_detail_record_analysis.ipynb](01_call_detail_record_analysis.ipynb)**: Use AI/ML to make call detail record analysis more auditable, faster, and easier to operationalize.
1. **[02_location_drift_spoofing_detection.ipynb](02_location_drift_spoofing_detection.ipynb)**: Use AI/ML to make location drift spoofing detection more auditable, faster, and easier to operationalize.
1. **[03_chat_app_artifact_linkage.ipynb](03_chat_app_artifact_linkage.ipynb)**: Use AI/ML to make chat app artifact linkage more auditable, faster, and easier to operationalize.
1. **[04_sim_swap_risk_scoring.ipynb](04_sim_swap_risk_scoring.ipynb)**: Use AI/ML to make sim swap risk scoring more auditable, faster, and easier to operationalize.
1. **[05_mobile_app_permission_abuse_classification.ipynb](05_mobile_app_permission_abuse_classification.ipynb)**: Use AI/ML to make mobile app permission abuse classification more auditable, faster, and easier to operationalize.
1. **[06_device_unlock_pattern_anomaly.ipynb](06_device_unlock_pattern_anomaly.ipynb)**: Use AI/ML to make device unlock pattern anomaly more auditable, faster, and easier to operationalize.
1. **[07_media_gallery_exfiltration_detection.ipynb](07_media_gallery_exfiltration_detection.ipynb)**: Use AI/ML to make media gallery exfiltration detection more auditable, faster, and easier to operationalize.
1. **[08_contact_graph_social_pattern_clustering.ipynb](08_contact_graph_social_pattern_clustering.ipynb)**: Use AI/ML to make contact graph social pattern clustering more auditable, faster, and easier to operationalize.
1. **[09_battery_network_forensic_correlation.ipynb](09_battery_network_forensic_correlation.ipynb)**: Use AI/ML to make battery network forensic correlation more auditable, faster, and easier to operationalize.
1. **[10_police_call_transcript_intent_analysis.ipynb](10_police_call_transcript_intent_analysis.ipynb)**: Use AI/ML to make police call transcript intent analysis more auditable, faster, and easier to operationalize.

## Standards and References

- NIST mobile device forensics guidance
- Android and iOS artifact extraction playbooks
- Call detail record analysis practices
