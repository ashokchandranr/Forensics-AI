# Forensics-AI

Practical AI/ML notebooks for forensics and investigative use cases.

Forensics-AI is a notebook-first repository for investigators, security researchers, and data scientists who want to understand how artificial intelligence can be applied across digital artifacts, network traffic, malware analysis, cloud infrastructure, financial crime, identity verification, and adjacent forensic domains.

The repository currently includes **97 notebooks** across **10 topic collections** and is explicitly benchmarked against the breadth of `Energy-AI` while enforcing a stricter notebook contract through local audits and CI.

## Quality Contract

- ~24 cells per notebook using a consistent 10-step investigative workflow
- 8-12 planned visualizations per notebook
- dedicated feature engineering step with a feature table
- explicit baseline benchmark before the stronger model
- explainability with feature importance and partial dependence
- operational triage function inside every notebook
- summary table and investigative handoff in every notebook
- domain depth anchored in evidence sources, standards, and analyst caveats

## Topic Collections

| Collection | Focus | Notebooks |
| --- | --- | ---: |
| [digital_file_artifact_analytics](digital_file_artifact_analytics/) | File-system, endpoint, and metadata evidence triage for anti-forensics and deleted-content recovery. | 12 |
| [network_traffic_intrusion_analytics](network_traffic_intrusion_analytics/) | Traffic, flow, and protocol analytics for intrusion triage, lateral movement, and exfiltration hunting. | 10 |
| [malware_behavior_classification](malware_behavior_classification/) | Static, dynamic, and execution-sequence analytics for malware family, loader, and anti-analysis detection. | 10 |
| [mobile_device_app_forensics](mobile_device_app_forensics/) | Call, app, geospatial, and device-state analytics for mobile-centric investigations. | 10 |
| [cloud_infrastructure_audit_forensics](cloud_infrastructure_audit_forensics/) | Identity, audit, and control-plane analytics for cloud compromise, drift, and storage misuse. | 10 |
| [multimedia_forgery_deepfake_detection](multimedia_forgery_deepfake_detection/) | Image, audio, video, and document authenticity workflows for manipulated-media investigations. | 9 |
| [financial_fraud_money_laundering_analytics](financial_fraud_money_laundering_analytics/) | Payments, entity, and transaction-network analytics for fraud, mule activity, and laundering typologies. | 8 |
| [biometric_identity_verification_analytics](biometric_identity_verification_analytics/) | Face, fingerprint, iris, and behavioral-biometric analytics for spoofing and session-takeover investigations. | 8 |
| [incident_response_timeline_reconstruction](incident_response_timeline_reconstruction/) | Multi-source event stitching, chronology confidence, and blast-radius analytics for active incidents. | 10 |
| [cyber_threat_intelligence_analytics](cyber_threat_intelligence_analytics/) | IOC, infrastructure, campaign, and external-signal analytics for CTI prioritization and attribution support. | 10 |

## Suggested Starting Points

- [digital_file_artifact_analytics/01_deleted_file_probability_estimation.ipynb](digital_file_artifact_analytics/01_deleted_file_probability_estimation.ipynb)
- [network_traffic_intrusion_analytics/02_beaconing_c2_detection.ipynb](network_traffic_intrusion_analytics/02_beaconing_c2_detection.ipynb)
- [malware_behavior_classification/01_ransomware_activity_classification.ipynb](malware_behavior_classification/01_ransomware_activity_classification.ipynb)
- [cloud_infrastructure_audit_forensics/01_aws_cloudtrail_anomaly_detection.ipynb](cloud_infrastructure_audit_forensics/01_aws_cloudtrail_anomaly_detection.ipynb)
- [incident_response_timeline_reconstruction/06_ransomware_blast_radius_estimation.ipynb](incident_response_timeline_reconstruction/06_ransomware_blast_radius_estimation.ipynb)

## Getting Started

### Option 1: Use Google Colab

Many notebooks run well in Colab.

1. Open a notebook from this repo in GitHub.
2. Open it in Google Colab or upload the notebook file manually.
3. If the notebook starts with a commented `!pip install` cell, uncomment it in a fresh runtime.
4. Run the notebook from top to bottom.

### Option 2: Run Locally with Jupyter

Most notebooks use a standard Python data stack. A simple local setup is:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install jupyterlab numpy pandas scikit-learn matplotlib seaborn scipy
jupyter lab
```

## Quality Audit

The repository includes `tools/forensics_repo_manager.py` with a strict audit that verifies notebook count, per-topic coverage, cell counts, visual markers, feature engineering, baselines, explainability, operational functions, and summary tables. A GitHub Actions workflow is included so the same audit can gate pull requests when this folder is used as a standalone repository.

## Important Note

This repository is for education, experimentation, and rapid prototyping. These notebooks should not be used as the sole basis for legal testimony, formal investigative reports, incident declarations, account freezes, or criminal proceedings without validation using real evidence, approved tools, and qualified domain review.

## License

This project is licensed under the [MIT License](LICENSE).
