---
description: How to calculate supply and borrow rate
---

# Interest Rate

## Borrow Interest Rate

To calculate Interest Rate:

$$
\begin{cases}
R_t = R_0 + \frac{U_t}{U_{optimal}}R_{slope1},& \text{if } U≤U_{optimal}\\
 R_t = R_0 + R_{slope1} + \frac{U_t - U_{optimal}}{1 - U_{optimal}}R_{slope2},& \text{else}
\end{cases}
$$

* $$U_{optimal}$$: **Optimal Utilization** - The utilisation rate targeted by asset reserve.
* $$R_0$$: **Base Borrow Rate** - Defines minimum borrow rate.
* $$R_{slope1}$$: **Rate Slope 1** - Constant representing the scaling of the interest rate versus the utilization, when utilization is below optimal.
* $$R_{slope2}$$: **Rate Slope 2 **_**-**_ Constant representing the scaling of the interest rate versus the utilization, when utilization is over optimal.

## Supply Rate

To calculate Supply APY:

$$
S_t = U_t V_t (1 - R_t)
$$

* $$S_t$$: **Supply Rate** - Expected APY.
* $$U_t$$: **Utilization Ratio** - Ratio between borrowed liquidity and total liquidity
* $$V_t$$: **Interest Rate** - Borrow interest rate.
* $$R_t$$: **Reserve Factor** - Protocol fee.
