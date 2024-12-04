# IAM Risk Classification Model Report

## Overall Performance Summary
- **Accuracy:** 51.01%
- **Macro Precision:** 22.70%
- **Macro Recall:** 35.46%
- **Macro F1 Score:** 20.22%

## Detailed Category Performance

### Credential Exposure
- Precision: 18.92%
- Recall: 100.00%
- F1 Score: 31.82%
- Summary: Good performance

### Data Access
- Precision: 25.00%
- Recall: 4.35%
- F1 Score: 7.41%
- Summary: Needs significant improvement

### Privilege Escalation
- Precision: 0.00%
- Recall: 0.00%
- F1 Score: 0.00%
- Summary: Needs significant improvement

### Resource Exposure
- Precision: 46.88%
- Recall: 37.50%
- F1 Score: 41.67%
- Summary: Moderate performance, could be improved

## Model Configuration
- Architecture: bert-base-uncased
- Ensemble Size: 3
- Training Parameters:
  - epochs: 5
  - batch_size: 16
  - learning_rate: 2e-05

## Dataset Information
- Training Set Size: 339
- Validation Set Size: 72
- Test Set Size: 74


Report generated on: 2024-12-03 09:40:37