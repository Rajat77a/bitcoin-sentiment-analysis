# Data Sources

The analysis expects two CSV files in the same working directory as the notebook.

## `historical_data.csv`

Trade-level Hyperliquid records used to evaluate trader behavior and performance. The notebook uses this data to calculate PnL, direction-level outcomes, token-level patterns, and account consistency.

## `fear_greed_index.csv`

Daily market sentiment readings from the Fear and Greed Index. These readings are mapped to trading dates so each trade can be analyzed under the matching sentiment regime.

Keep the date formats consistent before running the notebook, because the join between trades and sentiment is date-based.

