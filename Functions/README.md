##################
# Custom Functions
##################

This folder contains helper functions used for data generation and analysis.

## Available Functions

### `generate_dataset()`
Generates synthetic data with configurable categorical and numerical features, class imbalance, and specific outlier types.

**Arguments:**
* `type`: Numeric (`1`, `2`, or `3`) specifying the dataset variant.
* `n`: Integer. Total number of samples.
* `d`: Integer. Number of continuous (numerical) dimensions.
* `k`: Integer. Number of categorical variables.
* `m`: Integer. Number of levels per categorical variable.
* `imbalance_ratio`: Numeric. Ratio of majority to minority class.
