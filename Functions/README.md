# Custom Functions

This folder contains helper functions used for data generation and analysis.

## Available Functions

### `generate_dataset()`
Generates synthetic data with configurable categorical and numerical features, class imbalance, and specific outlier types.

**Arguments:**
* `type`: Numeric (`1`, `2`, or `3`) specifying the dataset variant. `1` - Both numerical and categorical contamination; `2` - Numerical-only contamination; `3` - Categorical-only contamination.
* `n`: Integer. Total number of observations.
* `d`: Integer. Number of continuous variables.
* `k`: Integer. Number of categorical variables.
* `m`: Integer. Number of categories per categorical variable.
* `imbalance_ratio`: Numeric. Ratio of majority to minority class. 
