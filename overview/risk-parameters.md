---
description: Parameters to manage liquidation risk
---

# Risk Parameters

## Concepts

* **Loan to Value** - Maximum amount of assets that can be borrowed with a specific collateral.
* **Liquidation Threshold** - Maximum percentage of value that can be borrowed against it.
* **Liquidation Bonus** - Bonus received by the liquidator that covers an under-collateralization.
* **Reserve Factor** - Bonus received by the protocol when value is withdrawn.

{% hint style="info" %}
These values are subject to change, as the Lendfinity DAO will be able to make proposals to update them.
{% endhint %}

These are the Risk parameters for each asset:

| Asset  | Base LTV | L. Threshold | L. Bonus | Reserve Factor | Strategy  |
| ------ | -------- | ------------ | -------- | -------------- | --------- |
| WBFT   | 75%      | 80%          | 5%       | 10%            | Volatile  |
| CHAPX  | 75%      | 80%          | 5%       | 10%            | Volatile  |
| ICP    | 75%      | 80%          | 5%       | 10%            | Volatile  |
| ckBTC  | 75%      | 80%          | 5%       | 10%            | Volatile  |
| ckETH  | 75%      | 80%          | 5%       | 10%            | Volatile  |
| ckUSDT | 75%      | 80%          | 5%       | 10%            | Stable #2 |
| ckUSDC | 75%      | 80%          | 5%       | 10%            | Stable #2 |
| SONIC  | 50%      | 80%          | 5%       | 10%            | Volatile  |
| DKP    | 75%      | 80%          | 5%       | 10%            | Volatile  |
| GLDT   | 75%      | 80%          | 5%       | 10%            | Volatile  |
| RICH   | 50%      | 75%          | 5%       | 10%            | Volatile  |
