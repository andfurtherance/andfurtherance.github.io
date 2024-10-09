---
layout: post
title: "Estimating Illiquidity Premium"
blog_title: "Estimating Illiquidity Premium"
date: 2024-10-09
categories: valuation, risk premium
---

If you’ve ever tried to value a private company, you’ve probably run into the thorny issue of **illiquidity**. Unlike public companies, where you can buy and sell shares fairly easily, private companies are much harder to trade. In some cases, it could take years to find a buyer for your shares—or you might not be able to sell them at all. Because of this, investors demand an **illiquidity premium**—an extra return to compensate for the fact that their money is tied up in an asset that can’t be easily sold.

But how do you calculate this illiquidity premium? It’s not something you can just look up in a database. It depends on the specific company, the market conditions, and the investor’s time horizon. And while there are some general guidelines, estimating the illiquidity premium is more of an art than a science.

## What Are We Trying to Measure?

Let’s start by defining what we’re actually trying to measure. When we talk about the **illiquidity premium**, we’re talking about the extra return investors expect for holding an asset that can’t be easily sold. In other words, it’s the price investors charge for locking up their money in something that’s hard to convert into cash.

The size of the illiquidity premium depends on two main factors:

1. **How illiquid the asset is**: Some private companies are more liquid than others. For example, a large, established private company might have a relatively active market for its shares, while a small startup might have almost no market at all.
    
2. **How long the investor expects to hold the asset**: The longer the investor expects to hold the asset, the higher the illiquidity premium should be. If you’re investing in a startup and you think it will take ten years before the company has an exit (like an IPO or acquisition), you should demand a higher premium than if you expect to sell your shares in two years.
    

So, the illiquidity premium is essentially a function of **time** and **marketability**. The more illiquid the asset, and the longer you expect to hold it, the higher the premium should be.

## Theoretical Approaches: Where to Start

A good place to start is with some theoretical approaches that have been developed to estimate illiquidity premiums. These models give us a framework to think about the problem, even if they don’t provide exact answers.

### Bid-Ask Spread as a Proxy

One of the simplest ways to think about illiquidity is to look at the **bid-ask spread**. In public markets, the bid-ask spread is the difference between the price buyers are willing to pay for an asset (the "bid") and the price sellers are asking for (the "ask"). The larger the spread, the more difficult it is to sell the asset without taking a loss, and the more illiquid the asset is.

For private companies, there’s no formal bid-ask spread because there’s no formal market. But you can think of the illiquidity premium as the difference between what you could realistically sell your shares for today and what you think they’re worth. The bigger that gap, the bigger the illiquidity premium.

For example, let’s say you own shares in a private company that you believe are worth $100 per share. But if you tried to sell them today, you’d probably only get $80 because there’s no active market for the shares. That $20 difference is effectively the illiquidity premium. In this case, the illiquidity premium would be 20% of the share price.

### The Private Equity vs. Public Equity Spread

Another common way to estimate the illiquidity premium is to compare the returns of **private equity** to **public equity**. Private equity investments are typically illiquid, while public equity investments are highly liquid. By looking at the historical difference in returns between private equity and public equity, we can get a rough sense of the illiquidity premium.

Studies have shown that private equity investments tend to outperform public equity by around 3-5% per year. This outperformance is often attributed to the illiquidity of private equity investments—investors demand a higher return to compensate for the fact that they can’t sell their shares easily.

So, one practical approach is to use this historical spread as a proxy for the illiquidity premium. If you’re valuing a private company, you could add 3-5% to the discount rate to account for illiquidity. This approach isn’t perfect, because the illiquidity premium can vary depending on the specific company and market conditions, but it gives you a useful starting point.

### The Option Pricing Model

A more sophisticated approach is to use **option pricing theory** to estimate the illiquidity premium. The idea here is that illiquidity is like owning a stock with a restriction on when you can sell it. In finance, this situation is similar to owning an option with a long expiration date—you can’t exercise the option (sell the stock) until a certain date in the future. The longer the restriction period, the less valuable the stock is today, because you’re giving up the ability to sell it when you want.

Using option pricing models like the **Black-Scholes model**, you can estimate how much value is lost due to illiquidity. The longer the expected holding period, the higher the illiquidity discount. This approach is very technical and requires some advanced math, but it’s useful for situations where you have a clear sense of how long the investor will be locked into the investment.

## Practical Methods: Real-World Approaches to Estimating Illiquidity Premiums

While the theoretical approaches are useful, they often don’t translate perfectly to real-world scenarios. In practice, estimating the illiquidity premium for a private company involves a lot of judgment and intuition. Here are some practical methods that investors use to calculate the illiquidity premium in the real world.

### 1. Comparable Transactions

One of the most practical ways to estimate the illiquidity premium is to look at **comparable transactions**. If similar private companies have been sold recently, you can compare the price they were sold for to the price of similar public companies. The difference in pricing often reflects the illiquidity premium.

For example, if a private company in the tech sector was sold for 10 times earnings, but similar public companies are trading at 12 times earnings, the 2x difference might be due to illiquidity. In this case, the implied illiquidity premium would be 16.7% (the difference between the private company’s multiple and the public company’s multiple, divided by the public company’s multiple).

This method works best when you have access to data on recent private transactions. It’s not always easy to find, especially for smaller companies, but if you can get it, it provides a solid, market-based estimate of the illiquidity premium.

### 2. Discount for Lack of Marketability (DLOM)

Another common method is to apply a **Discount for Lack of Marketability (DLOM)**. This is a percentage discount applied to the value of a private company to reflect the fact that the shares are harder to sell than those of a public company. The DLOM is essentially a proxy for the illiquidity premium.

There are several ways to estimate the DLOM, but one of the most practical is to use **restricted stock studies**. These studies look at the difference in price between restricted shares (which can’t be sold for a certain period) and unrestricted shares of the same company. The difference in price reflects the illiquidity premium.

Historically, these studies have shown that restricted shares trade at a discount of 15-30% compared to unrestricted shares. So, if you’re valuing a private company, you could apply a DLOM of 15-30% to reflect the illiquidity of the shares. The exact percentage you choose will depend on how illiquid the company is. For a small startup with no active market for its shares, you might use the higher end of the range (closer to 30%). For a more established private company with some liquidity, you might use the lower end (closer to 15%).

### 3. Time to Liquidity

Another practical approach is to estimate the **time to liquidity** and adjust the discount rate accordingly. The idea here is that the longer it will take for the investor to sell their shares, the higher the illiquidity premium should be.

For example, let’s say you’re valuing a startup, and you think it will take five years for the company to have an exit (such as an IPO or acquisition). You might decide that the illiquidity premium should be 1% for every year the investor is expected to be locked into the investment. In this case, you would apply a 5% illiquidity premium to reflect the five-year holding period.

This method is intuitive because it ties the illiquidity premium directly to the expected time horizon. The longer the investor’s money is locked up, the higher the premium should be.

### 4. Investor Surveys

Another real-world method is to look at **investor surveys**. Some organizations conduct surveys of private equity and venture capital investors to get a sense of how much of a premium they demand for illiquidity. These surveys can give you a rough idea of what the market is currently pricing in for illiquidity.

For example, a survey might show that private equity investors are currently demanding an extra 3-5% return for illiquidity, depending on the size and stage of the company. While this method isn’t as precise as some of the others, it gives you a useful benchmark based on real-world investor expectations.

## Intuitive Heuristics for Illiquidity Premiums

In addition to the more formal methods, there are some intuitive heuristics you can use to estimate the illiquidity premium. These aren’t based on hard data, but they can help guide your thinking.

### 1. Think About Opportunity Cost

One way to think about the illiquidity premium is in terms of **opportunity cost**. If you invest in a private company and can’t sell your shares for several years, you’re giving up the opportunity to invest in more liquid assets that might offer similar returns. The illiquidity premium should compensate you for that lost flexibility.

Ask yourself, _What other investments could I make that offer similar returns but are more liquid?_ If you can think of several liquid investments that offer comparable returns, the illiquidity premium should be higher because you’re giving up a lot of flexibility. If there aren’t many liquid alternatives that offer similar returns, the illiquidity premium can be lower.

### 2. Use the “Pain Threshold” Test

Another heuristic is to ask, _How painful would it be to hold this investment for the next several years without being able to sell it?_ The more painful it would be, the higher the illiquidity premium should be. This is a subjective test, but it forces you to think about the practical realities of illiquidity. If the company is risky, or if the market is volatile, it’s going to be more painful to hold an illiquid investment, and you should demand a higher return.

## Conclusion

Estimating the illiquidity premium for private companies is both practical and intuitive. There are theoretical models you can use as a guide—like bid-ask spreads, private equity vs. public equity comparisons, and option pricing models—but in practice, it often comes down to judgment and experience.

The best way to estimate the illiquidity premium is to combine multiple approaches. Look at comparable transactions, apply a Discount for Lack of Marketability (DLOM), and think carefully about the time to liquidity. Use investor surveys and historical data as benchmarks, but don’t be afraid to rely on intuition and heuristics. The illiquidity premium is ultimately about compensating investors for the risk of being locked into an investment, and the more clearly you understand that risk, the better your estimates will be.
