---
layout: post
title: Using Option Pricing to Estimate Illiquidity Premium
blog_title: Using Option Pricing to Estimate Illiquidity Premium
date: 2024-10-10
category: valuation. finance tools, illiquidity, risk premium
---

Most people think of the **Black Scholes model**  as something you use to price options, and they're right. But there's more to it than that. What if you could use the same model to estimate the illiquidity premium?

Let's first clarify a few terms.
## What is Illiquidity?
Liquidity refers to how quickly and easily an asset can be converted into cash without significantly affecting its price. Stocks of large public companies are generally highly liquid because they trade in high volumes on public markets. You can sell the stock in minutes and get close to the market price. On the other hand, a private equity investment or real estate property is much less liquid. It might take weeks, months or even years to find a buyer, and in the meantime, you might have to accept a significant discount to sell quickly.

The illiquidity premium is the extra return that investors demand for holding an illiquid asset. For example, if a liquid stock offers a 7% expected return, an illiquid real estate investment might offer 10% or 12%, with the difference representing the illiquidity premium. Essentially, you're being compensated for the inconveniences and risk of not being able to sell the asset quickly.

> The invisible hand should ensure that illiquid assets offer higher returns because investors will not choose such assets over liquid assets with similar returns if they do not.

But how do we quantify that premium? This is where the option pricing model can help.
## The Black-Scholes Model: A Primer
Black-Scholes model is the foundation of modern option pricing. It is a mathematical model used to determine the fair price of options. An option is a financial contract that gives the holder the right, but not the obligation, to buy or sell an asset at a predetermined price (the **strike price**) before a certain date (the **expiration date**).

The model takes into account several factors:
1. The current price of the asset
2. The strike price (the price at which you can buy or sell the asset)
3. The time to expiration (how long until the option expires)
4. The risk-free rate (the return you'd get on a risk-free investment, like a government bond)
5. The volatility of the asset (how much the price of the asset fluctuates)

The formula is a bit intimidating at first glance, but the core idea is simple: it uses these factors to estimate how much an option should be worth today, given the uncertainty of the asset's future price.

$C = S_0N(d_1)-X_e^{rT}N(d_2)$

Where:
- $C$ is the price of the call option
- $S_0$ is the current price of the asset
- $X$ is the strike price
- $r$ is the risk-free interest rate
- $T$ is the time to expiration
- $N(d_1)$ and $N(d_2)$ is the probabilities derived from the volatility of the asset

The key takeaway here is that volatility plays a critical roles in determining the price of an option. The more volatile the asset, the more valuable the option, because there's a higher chance it will end up "in the money"--meaning the option will be worth exercising.

## Illiquidity as Implied Volatility
Imagine you own an asset that is difficult to sell--a private business, real estate, or a sparsely traded stock. The illiquidity of that asset means there's more uncertainty about its future price, because you might not be able to sell it quickly at the current market price.

In other words, illiquidity introduces risk, and in financial markets, risk and volatility are closely related. When an asset is illiquid, its price is subject to larger fluctuations because there are fewer buyers and sellers. This is especially true in times of market stress, when liquidity can dry up completely.

How can you quantify that risk? One way is by using the option pricing model to estimate implied volatility of the asset. Implied volatility level that makes the Black-Scholes model predicted option price match the actual market price of an option. It's essentially the market's guess of how risky the asset is.

We can flip this around: instead of using implied volatility to price an option, we can use it to estimate the impact of illiquidity on the asset's price. The more illiquid the asset, the higher the implied volatility. And the higher the implied volatility, the greater the illiquidity premium.

## An Example
Imagine you're trying to value two stocks. Stock A is highly liquid, traded on a major exchange with its of daily volume, while Stock B is illiquid, traded on small over-the-counter market with very few buyers and sellers.

Both stocks are currently priced at NPR 100, and you're trying to estimate how much extra return you should demand for holding the illiquid Stock B. You know Stock A has an annualized volatility of 20%, but Stock B's volatility is uncertain because of its illiquidity.

Here's what you can do: use the Black-Scholes model to estimate the implied volatility for Stock B by treating it like an option. You can model it as a European call option on a liquid stock, where the illiquidity represents the extra risk of not being able to exercise the option at any time.

1. Use the Black-Scholes model to price Stock A's volatility. With a current market price of NPR 100, a strike price of NPR 100, a risk-free rate of 2% and a time to expiration of one year, Stock A's implied volatility is straightforward: 20%.
2. Now, apply the same model for Stock B, but with one key difference: introduce a higher implied volatility to reflect its illiquidity. Let's say you estimate the implied volatility for Stock B to be 30%, based on the historical price swings and the lack of trading activity.
3. The difference between the two implied volatilities represents the extra risk (and therefore the extra return) you should demand for holding the illiquid stock.

In this case, the illiquidity premium would be the difference in expected returns derived by the higher volatility. If you price the stock using a higher discount rate to account for the additional volatility, you'd arrive at a higher expected return for Stock B to compensate for its illiquidity.

## Why This Matters
Illiquidity is a real risk, and investors should demand compensation for taking it on. By using the option pricing model to estimate the implied volatility of an illiquid asset, you can quantify that risk and build it into your valuation models.

More importantly, this approach shifts the way we think about illiquidity. Instead of just seeing it as some vague risk that's hard to quantify, we can think about it in terms of volatility and uncertainty. Illiquidity makes an asset more volatile because its's harder to buy and sell. And the more volatile an asset is, the higher the return you should demand for holding it.

In a way, this is a more honest approach to valuing illiquid assets. Rather than pretending that illiquidity is some abstract concept, we treat it as a concrete risk that can be measured and compensated for. And once you start thinking about illiquidity in terms of volatility, you can use all the tools of modern finance--like the Black-Scholes model--to estimate its impact on value.
