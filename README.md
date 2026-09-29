# A/B Test: Cookie Cats Gate Placement

Analysis of a mobile game experiment testing whether moving the first progression gate from level 30 to level 40 affects player retention.

**Data:** ~90,000 players, randomly assigned to gate_30 or gate_40 (Kaggle: Mobile Games A/B Testing – Cookie Cats)
**Methods:** two-proportion z-test, 95% confidence intervals, power analysis (Python, pandas, statsmodels, matplotlib)

**Result:** 7-day retention was significantly higher with the gate at level 30 (19.02% vs 18.20%, p = 0.0016). 1-day retention showed no significant difference (p = 0.074).
**Recommendation:** keep the gate at level 30.

**Limitations:** retention only; revenue and engagement not measured.

See `ab_test.ipynb` for the full analysis.
