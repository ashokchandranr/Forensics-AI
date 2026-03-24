# Multimedia Forgery & Deepfake Detection

Image, audio, video, and document authenticity workflows for manipulated-media investigations.

## Operational Question

These notebooks focus on whether to escalate for specialist review, preserve source media, or challenge provenance claims.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| Image and video bitstreams | Compression, resampling, and frame inconsistency clues | Platform transcoding can inject benign artifacts |
| Audio spectral features | Prosody, phase, and codec mismatch patterns | Call-center compression changes the spectrum |
| Metadata and capture provenance | EXIF, edit chain, and export path anomalies | Social apps strip or rewrite metadata |
| Document and scan structure | Layering, paste regions, and OCR mismatch indicators | Printer-scanner pipelines create repeated textures |

## Notebook Catalog

1. **[01_face_swap_artifact_detection.ipynb](01_face_swap_artifact_detection.ipynb)**: Use AI/ML to make face swap artifact detection more auditable, faster, and easier to operationalize.
1. **[02_audio_frequency_artifact_detection.ipynb](02_audio_frequency_artifact_detection.ipynb)**: Use AI/ML to make audio frequency artifact detection more auditable, faster, and easier to operationalize.
1. **[03_video_frame_inconsistency_scoring.ipynb](03_video_frame_inconsistency_scoring.ipynb)**: Use AI/ML to make video frame inconsistency scoring more auditable, faster, and easier to operationalize.
1. **[04_voice_clone_prosody_detection.ipynb](04_voice_clone_prosody_detection.ipynb)**: Use AI/ML to make voice clone prosody detection more auditable, faster, and easier to operationalize.
1. **[05_image_metadata_provenance_mismatch.ipynb](05_image_metadata_provenance_mismatch.ipynb)**: Use AI/ML to make image metadata provenance mismatch more auditable, faster, and easier to operationalize.
1. **[06_copy_move_region_forensics.ipynb](06_copy_move_region_forensics.ipynb)**: Use AI/ML to make copy move region forensics more auditable, faster, and easier to operationalize.
1. **[07_recompression_ela_risk_scoring.ipynb](07_recompression_ela_risk_scoring.ipynb)**: Use AI/ML to make recompression ela risk scoring more auditable, faster, and easier to operationalize.
1. **[08_lip_sync_manipulation_detection.ipynb](08_lip_sync_manipulation_detection.ipynb)**: Use AI/ML to make lip sync manipulation detection more auditable, faster, and easier to operationalize.
1. **[09_document_scan_tamper_classification.ipynb](09_document_scan_tamper_classification.ipynb)**: Use AI/ML to make document scan tamper classification more auditable, faster, and easier to operationalize.

## Standards and References

- C2PA provenance guidance
- NIST media forensics publications
- Deepfake detection benchmark literature
