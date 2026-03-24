# Cyber Threat Intelligence Analytics

IOC, infrastructure, campaign, and external-signal analytics for CTI prioritization and attribution support.

## Operational Question

These notebooks focus on which campaigns to track, which indicators to publish, and which actor links warrant analyst confidence.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| IOC feeds and sinkhole data | Confidence drift, prevalence, and overlap | Feed recency and vendor confidence vary |
| Domain and hosting telemetry | Registration, reuse, and infrastructure pivoting | Shared hosting creates contamination |
| Phishing and brand-abuse samples | Template reuse and lure evolution | Seasonal campaigns change content sharply |
| Dark web and vulnerability chatter | Credential resale, exploit demand, and threat actor focus | Collection bias affects apparent volume |

## Notebook Catalog

1. **[01_phishing_campaign_clustering.ipynb](01_phishing_campaign_clustering.ipynb)**: Use AI/ML to make phishing campaign clustering more auditable, faster, and easier to operationalize.
1. **[02_ioc_confidence_fusion.ipynb](02_ioc_confidence_fusion.ipynb)**: Use AI/ML to make ioc confidence fusion more auditable, faster, and easier to operationalize.
1. **[03_ttp_attribution_scoring.ipynb](03_ttp_attribution_scoring.ipynb)**: Use AI/ML to make ttp attribution scoring more auditable, faster, and easier to operationalize.
1. **[04_domain_generation_pattern_detection.ipynb](04_domain_generation_pattern_detection.ipynb)**: Use AI/ML to make domain generation pattern detection more auditable, faster, and easier to operationalize.
1. **[05_dark_web_credential_risk_prioritization.ipynb](05_dark_web_credential_risk_prioritization.ipynb)**: Use AI/ML to make dark web credential risk prioritization more auditable, faster, and easier to operationalize.
1. **[06_vulnerability_exploit_trend_forecasting.ipynb](06_vulnerability_exploit_trend_forecasting.ipynb)**: Use AI/ML to make vulnerability exploit trend forecasting more auditable, faster, and easier to operationalize.
1. **[07_brand_impersonation_page_detection.ipynb](07_brand_impersonation_page_detection.ipynb)**: Use AI/ML to make brand impersonation page detection more auditable, faster, and easier to operationalize.
1. **[08_malspam_infrastructure_link_analysis.ipynb](08_malspam_infrastructure_link_analysis.ipynb)**: Use AI/ML to make malspam infrastructure link analysis more auditable, faster, and easier to operationalize.
1. **[09_actor_infrastructure_overlap_clustering.ipynb](09_actor_infrastructure_overlap_clustering.ipynb)**: Use AI/ML to make actor infrastructure overlap clustering more auditable, faster, and easier to operationalize.
1. **[10_campaign_severity_early_warning.ipynb](10_campaign_severity_early_warning.ipynb)**: Use AI/ML to make campaign severity early warning more auditable, faster, and easier to operationalize.

## Standards and References

- MITRE ATT&CK
- STIX / TAXII design guidance
- Threat intel structured analytic techniques
