# Digital File Artifact Analytics

File-system, endpoint, and metadata evidence triage for anti-forensics and deleted-content recovery.

## Operational Question

These notebooks focus on which artifacts to preserve first and which hosts require deeper disk or memory imaging.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| $MFT / USN Journal | Deletion churn, rename bursts, and sequence reuse | Clock rollback and journal truncation can mask history |
| Prefetch / LNK / SRUM | Program execution and user interaction traces | Application control changes can alter artifact coverage |
| Registry hives | Persistence, recent documents, mounted devices | Live collection can mutate volatile keys |
| Browser and document metadata | Exfiltration path, authorship, and provenance clues | Time-zone normalization must stay explicit |

## Notebook Catalog

1. **[01_deleted_file_probability_estimation.ipynb](01_deleted_file_probability_estimation.ipynb)**: Use AI/ML to make deleted file probability estimation more auditable, faster, and easier to operationalize.
1. **[02_registry_key_tampering_detection.ipynb](02_registry_key_tampering_detection.ipynb)**: Use AI/ML to make registry key tampering detection more auditable, faster, and easier to operationalize.
1. **[03_browser_history_session_reconstruction.ipynb](03_browser_history_session_reconstruction.ipynb)**: Use AI/ML to make browser history session reconstruction more auditable, faster, and easier to operationalize.
1. **[04_mft_timeline_gap_detection.ipynb](04_mft_timeline_gap_detection.ipynb)**: Use AI/ML to make $mft timeline gap detection more auditable, faster, and easier to operationalize.
1. **[05_usb_device_artifact_correlation.ipynb](05_usb_device_artifact_correlation.ipynb)**: Use AI/ML to make usb device artifact correlation more auditable, faster, and easier to operationalize.
1. **[06_lnk_prefetch_execution_profiling.ipynb](06_lnk_prefetch_execution_profiling.ipynb)**: Use AI/ML to make lnk prefetch execution profiling more auditable, faster, and easier to operationalize.
1. **[07_shadow_copy_restore_gap_analysis.ipynb](07_shadow_copy_restore_gap_analysis.ipynb)**: Use AI/ML to make shadow copy restore gap analysis more auditable, faster, and easier to operationalize.
1. **[08_archive_steg_hidden_content_scoring.ipynb](08_archive_steg_hidden_content_scoring.ipynb)**: Use AI/ML to make archive steg hidden content scoring more auditable, faster, and easier to operationalize.
1. **[09_email_attachment_provenance_scoring.ipynb](09_email_attachment_provenance_scoring.ipynb)**: Use AI/ML to make email attachment provenance scoring more auditable, faster, and easier to operationalize.
1. **[10_logfile_tamper_evidence_detection.ipynb](10_logfile_tamper_evidence_detection.ipynb)**: Use AI/ML to make logfile tamper evidence detection more auditable, faster, and easier to operationalize.
1. **[11_filesystem_entropy_ransomware_screening.ipynb](11_filesystem_entropy_ransomware_screening.ipynb)**: Use AI/ML to make filesystem entropy ransomware screening more auditable, faster, and easier to operationalize.
1. **[12_document_metadata_fraud_scoring.ipynb](12_document_metadata_fraud_scoring.ipynb)**: Use AI/ML to make document metadata fraud scoring more auditable, faster, and easier to operationalize.

## Standards and References

- NIST SP 800-86
- Carrier, File System Forensic Analysis
- SANS DFIR artifact triage guidance
