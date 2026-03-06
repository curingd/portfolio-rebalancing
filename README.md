# Portfolio Rebalancing
This project testing periodic and threshold rebalancing strategies against no rebalancing for returns on randomly generated portfolios of US stocks.

Returns data from a 20 year period is used and transactions costs are modelled on a basis proportional to trade sizes.

The aim of the project was to consider whether periodic rebalancing, threshold rebalancing or no rebalancing generated the highest return "on average" on either an absolute or risk-adjusted basis.

The conclusions of the project are:

1. Both periodic and threshold rebalancing stategies negatively affected median returns;
2. Transactions costs had an insignificant effect on returns.
3. Only periodic rebalancing at frequent periods (daily to weekly) with minimal transactions costs produced superior risk-adjusted returns than without rebalancing.

Known limitations of the project are:

1. The data used was subject to survivorship and lookahead biases (unadjusted for delistings);
2. The 2006-2026 period used crosses multiple economic regimes which may have impacted the results.
