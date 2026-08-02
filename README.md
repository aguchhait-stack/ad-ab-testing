# Ad Campaign A/B Test

An advertising agency works with a brand called SmartAD to develop interactive ads. This new advertisement is expected to attract a large number of users to fill out their questionnaires. To determine whether the interactive ad generated more responses to the questionnaire, they conducted an A/B test. This project analyzes the results to determine whether the new ad design affects user behavior in responding to the BIO questionnaire.

## Key Finding

- SRM check: groups were not balanced as expected (p < 0.05) — flagged as a data quality concern
- Main test: no statistically significant difference in conversion rate between groups (p = 0.556)
- Given the SRM result, this finding is treated as provisional rather than conclusive — in a production setting, the imbalance would need investigating before trusting the result

![A/B test results](outputs/ab_test_results.png)

## 🚀 Quick Start

```bash
# Clone repository
git clone https://github.com/aguchhait-stack/ad-ab-testing.git
cd ad-ab-testing

# Install dependencies
pip install -r requirements.txt

# Explore notebook
jupyter notebook notebook.ipynb
```

## 📄 License & Citation

[AdSmart AB Testing dataset](https://www.kaggle.com/datasets/osuolaleemmanuel/ad-ab-testing) (Kaggle).

## 👨‍💻 Author

**Arijit Guchhait**
[LinkedIn](https://www.linkedin.com/in/guchhaitarijit/)