# Financial Fraud & Money Laundering Analytics

Payments, entity, and transaction-network analytics for fraud, mule activity, and laundering typologies.

## Operational Question

These notebooks focus on whether to hold funds, enrich counterparties, or escalate to enhanced due diligence.

## Evidence Anchors

| Source | Why It Matters | Caveat |
| --- | --- | --- |
| Transaction ledgers | Velocity, structuring, and round-tripping patterns | Seasonality and payroll cycles create normal bursts |
| Customer and entity KYC | Shared owners, nominees, and shell risk clues | Corporate hierarchies can be incomplete |
| Merchant and channel telemetry | Card testing, device switching, and origin anomalies | Marketing campaigns change customer behavior |
| Crypto and payout traces | Mixer exposure, hop counts, and withdrawal timing | Privacy tools are not automatically illicit |

## Notebook Catalog

1. **[01_transaction_smurfing_pattern_detection.ipynb](01_transaction_smurfing_pattern_detection.ipynb)**: Use AI/ML to make transaction smurfing pattern detection more auditable, faster, and easier to operationalize.
1. **[02_shell_company_network_scoring.ipynb](02_shell_company_network_scoring.ipynb)**: Use AI/ML to make shell company network scoring more auditable, faster, and easier to operationalize.
1. **[03_mule_account_behavior_classification.ipynb](03_mule_account_behavior_classification.ipynb)**: Use AI/ML to make mule account behavior classification more auditable, faster, and easier to operationalize.
1. **[04_trade_based_money_laundering_risk.ipynb](04_trade_based_money_laundering_risk.ipynb)**: Use AI/ML to make trade based money laundering risk more auditable, faster, and easier to operationalize.
1. **[05_invoice_round_tripping_detection.ipynb](05_invoice_round_tripping_detection.ipynb)**: Use AI/ML to make invoice round tripping detection more auditable, faster, and easier to operationalize.
1. **[06_card_testing_burst_detection.ipynb](06_card_testing_burst_detection.ipynb)**: Use AI/ML to make card testing burst detection more auditable, faster, and easier to operationalize.
1. **[07_crypto_mixing_exposure_scoring.ipynb](07_crypto_mixing_exposure_scoring.ipynb)**: Use AI/ML to make crypto mixing exposure scoring more auditable, faster, and easier to operationalize.
1. **[08_procurement_kickback_signal_fusion.ipynb](08_procurement_kickback_signal_fusion.ipynb)**: Use AI/ML to make procurement kickback signal fusion more auditable, faster, and easier to operationalize.

## Standards and References

- FATF risk-based approach guidance
- FinCEN suspicious activity reporting themes
- ACAMS typology references
