# Biometric Identity Verification Analytics

Face, fingerprint, iris, and behavioral-biometric analytics for spoofing and session-takeover investigations.

## Operational Question

These notebooks focus on whether to step up authentication, review enrollment quality, or challenge biometric evidence.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| Capture quality metrics | Blur, illumination, and template stability | Low-end sensors degrade quality even for genuine users |
| Liveness and interaction traces | Challenge-response timing and spoof cues | Accessibility workflows change timing |
| Matcher scores | Identity overlap, impostor spread, and calibration | Thresholds drift across vendors |
| Behavioral biometrics | Typing, touch, and session consistency | Stress and travel can change behavior |

## Notebook Catalog

1. **[01_presentation_attack_liveness_detection.ipynb](01_presentation_attack_liveness_detection.ipynb)**: Use AI/ML to make presentation attack liveness detection more auditable, faster, and easier to operationalize.
1. **[02_face_match_score_calibration.ipynb](02_face_match_score_calibration.ipynb)**: Use AI/ML to make face match score calibration more auditable, faster, and easier to operationalize.
1. **[03_fingerprint_template_spoof_risk.ipynb](03_fingerprint_template_spoof_risk.ipynb)**: Use AI/ML to make fingerprint template spoof risk more auditable, faster, and easier to operationalize.
1. **[04_iris_capture_quality_classification.ipynb](04_iris_capture_quality_classification.ipynb)**: Use AI/ML to make iris capture quality classification more auditable, faster, and easier to operationalize.
1. **[05_keystroke_biometric_impersonation_detection.ipynb](05_keystroke_biometric_impersonation_detection.ipynb)**: Use AI/ML to make keystroke biometric impersonation detection more auditable, faster, and easier to operationalize.
1. **[06_behavioral_biometrics_session_takeover.ipynb](06_behavioral_biometrics_session_takeover.ipynb)**: Use AI/ML to make behavioral biometrics session takeover more auditable, faster, and easier to operationalize.
1. **[07_document_selfie_match_forensics.ipynb](07_document_selfie_match_forensics.ipynb)**: Use AI/ML to make document selfie match forensics more auditable, faster, and easier to operationalize.
1. **[08_multimodal_identity_fusion_scoring.ipynb](08_multimodal_identity_fusion_scoring.ipynb)**: Use AI/ML to make multimodal identity fusion scoring more auditable, faster, and easier to operationalize.

## Standards and References

- ISO/IEC 30107 PAD guidance
- NIST FRVT publications
- Biometric system calibration best practices
