# Portfolio Rebalancing
This project testing periodic and threshold rebalancing strategies against no rebalancing for bootstrapped returns on randomly generated portfolios of US stocks.

Returns data from a 20 year period is used and transactions costs are modelled on a basis proportional to trade sizes.

The aim of the project was to consider whether periodic rebalancing, threshold rebalancing or no rebalancing generated the highest return "on average".

The conclusions of the project are:

1. Both periodic and threshold rebalancing stategies negatively affected mean returns;
2. Transactions costs had an insignificant effect on returns.

Known limitations of the project are:

1. The data used was subject to survivorship and lookahead biases (unadjusted for delistings);
2. Bootstrapping may have removed volatility clustering present in real-world returns;
3. The effect of rebalancing on risk or risk-adjusted returns was not considered.
