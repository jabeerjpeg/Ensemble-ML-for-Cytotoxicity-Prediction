
NANOPARTICLE TOXICITY MODEL - VERSION 1.0
Frozen: 2025-11-01 16:59

PERFORMANCE SUMMARY:
- Macro F1 Score: 0.9595 (95% CI: 0.8985 - 1.0000)
- Balanced Accuracy: 0.9444 (95% CI: 0.8675 - 1.0000)
- Overall Accuracy: 0.9677

MODEL ARCHITECTURE:
- Base Models: ['rf', 'lgb']
- Meta-Learner: LogisticRegression
- Training Samples: 246
- Features: 22
- Classes: 3 ([0, 1, 2])

CHANGES IN V1:
- Final stacked ensemble configuration
- Confidence intervals added via bootstrapping
- Comprehensive metadata and versioning
- Feature importance visualization
- Proper class alignment handling

USAGE:
This model is now frozen for production use.
All future changes should be tracked as new versions.
