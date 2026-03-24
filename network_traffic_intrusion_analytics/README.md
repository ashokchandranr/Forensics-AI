# Network Traffic Intrusion Analytics

Traffic, flow, and protocol analytics for intrusion triage, lateral movement, and exfiltration hunting.

## Operational Question

These notebooks focus on whether to isolate hosts, block destinations, or expand packet capture scope.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| NetFlow / Zeek summaries | Volume shifts, beacon periodicity, and east-west movement | Sampling can undercount short sessions |
| DNS and proxy logs | Domain generation, tunneling, and egress path changes | Resolver caching changes frequency signatures |
| TLS / JA3 fingerprints | Client impersonation and unusual tooling families | Shared libraries can collide on fingerprints |
| Authentication and VPN logs | Impossible travel, remote access spikes, and account abuse | Burstiness around maintenance windows is normal |

## Notebook Catalog

1. **[01_lateral_movement_anomaly_detection.ipynb](01_lateral_movement_anomaly_detection.ipynb)**: Use AI/ML to make lateral movement anomaly detection more auditable, faster, and easier to operationalize.
1. **[02_beaconing_c2_detection.ipynb](02_beaconing_c2_detection.ipynb)**: Use AI/ML to make beaconing c2 detection more auditable, faster, and easier to operationalize.
1. **[03_data_exfiltration_flow_scoring.ipynb](03_data_exfiltration_flow_scoring.ipynb)**: Use AI/ML to make data exfiltration flow scoring more auditable, faster, and easier to operationalize.
1. **[04_dns_tunneling_pattern_detection.ipynb](04_dns_tunneling_pattern_detection.ipynb)**: Use AI/ML to make dns tunneling pattern detection more auditable, faster, and easier to operationalize.
1. **[05_internal_scan_campaign_clustering.ipynb](05_internal_scan_campaign_clustering.ipynb)**: Use AI/ML to make internal scan campaign clustering more auditable, faster, and easier to operationalize.
1. **[06_tls_fingerprint_risk_classification.ipynb](06_tls_fingerprint_risk_classification.ipynb)**: Use AI/ML to make tls fingerprint risk classification more auditable, faster, and easier to operationalize.
1. **[07_east_west_segmentation_breach_risk.ipynb](07_east_west_segmentation_breach_risk.ipynb)**: Use AI/ML to make east west segmentation breach risk more auditable, faster, and easier to operationalize.
1. **[08_proxy_evasion_traffic_profiling.ipynb](08_proxy_evasion_traffic_profiling.ipynb)**: Use AI/ML to make proxy evasion traffic profiling more auditable, faster, and easier to operationalize.
1. **[09_rdp_bruteforce_session_detection.ipynb](09_rdp_bruteforce_session_detection.ipynb)**: Use AI/ML to make rdp bruteforce session detection more auditable, faster, and easier to operationalize.
1. **[10_ot_network_protocol_misuse_detection.ipynb](10_ot_network_protocol_misuse_detection.ipynb)**: Use AI/ML to make ot network protocol misuse detection more auditable, faster, and easier to operationalize.

## Standards and References

- MITRE ATT&CK
- Zeek protocol logging guidance
- NIST SP 800-61
