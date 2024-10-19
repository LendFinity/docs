---
description: Parameters to manage liquidation risk
---

# Risk Parameters

## Concepts

* **Loan to Value** - Maximum amount of assets that can be borrowed with a specific collateral.
* **Liquidation Threshold** - Maximum percentage of value that can be borrowed against it.
* **Liquidation Bonus** - Bonus received by the liquidator that covers an under-collateralization.

{% hint style="info" %}
These values are subject to change, as the Lendfinity DAO will be able to make proposals to update them.
{% endhint %}

These are the Risk parameters for each asset:

| Asset  | Base LTV | Liquidation Threshold | Liquidation Bonus | Reserve Factor | Strategy  |
| ------ | -------- | --------------------- | ----------------- | -------------- | --------- |
| WBFT   | 50%      | 75%                   | 5%                | 10%            | Volatile  |
| ICP    | 50%      | 75%                   | 5%                | 10%            | Volatile  |
| ckBTC  | 50%      | 75%                   | 5%                | 10%            | Volatile  |
| ckUSDT | 50%      | 75%                   | 5%                | 10%            | Stable #1 |
| ckUSDC | 50%      | 75%                   | 5%                | 10%            | Stable #1 |
