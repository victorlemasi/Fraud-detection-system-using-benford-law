# Fraud-detection-system-using-benford-law
what the system does:

1. Takes numerical data as input (e.g., financial transactions, account balances)
2. Calculates the distribution of first digits in the dataset
3. Compares it to the expected Benford's Law distribution
4. Performs statistical analysis (chi-square test)
5. Generates a risk score and detailed analysis
6. Provides visualization capabilities

To use this system, you would:

```python
# Create an instance
analyzer = BenfordAnalyzer()

# Analyze your data
results = analyzer.analyze(your_data)

# View the results
print(results)

# Generate visualization
analyzer.plot_distributions(your_data)
```

The system provides:
- Statistical test results (chi-square and p-value)
- Risk score (0-100)
- Detailed deviations from expected frequencies
- Visual comparison through plots
