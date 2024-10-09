---
layout: post
title: "Undestanding Dicounted Cash Flow"
blog_title: "Understanding Discoutned Cash Flow"
date: 2024-10-09
categories: valuation, DCF
published: true
---

When it comes to valuing companies, few tools are as powerful—or misunderstood—as **Discounted Cash Flow (DCF)** analysis. On the surface, DCF seems like a straightforward formula: take the company’s expected future cash flows and discount them to the present. But in reality, DCF is more than just a mathematical model. It's a way of thinking about value, risk, and time. And like most valuable tools, its effectiveness depends on how well you understand it.

DCF is often misused. People plug numbers into a spreadsheet, generate a value, and walk away, forgetting that every assumption they made—about growth, risk, the future—affects the final result. The truth is, DCF is part science, part art. There’s no single "right" answer, and the model is only as good as the inputs you provide. But if you understand the mechanics of DCF and the intuition behind it, it gives you a framework for thinking clearly about what a company is worth.

## The Core Idea of DCF: It’s About Time and Risk

At its core, DCF is about two things: **time** and **risk**. The basic idea is that money today is worth more than money in the future. That’s because you can invest money today and earn a return on it. So if someone offers you $100 today or $100 next year, you’d prefer to have the money today, because you could invest it and turn it into something more than $100 by next year.

This is where the concept of **discounting** comes in. When you discount a future cash flow, you’re adjusting it to reflect the fact that money in the future is worth less than money today. How much less depends on two things: how far in the future the cash flow is, and how risky it is. The further in the future the cash flow, and the riskier the company, the more you discount it.

In a typical DCF model, you estimate a company’s future cash flows for a certain number of years—say, 5 or 10 years—and then you **discount** those cash flows back to the present using a discount rate that reflects the risk of the company. The result is the **present value** of the company’s future cash flows, which gives you an estimate of the company’s intrinsic value.

So DCF is really about understanding how time and risk affect value. The longer you have to wait for a cash flow, and the riskier the company, the less that future cash flow is worth today. But if the company is growing fast and is relatively low risk, its future cash flows are worth more.

## Step-by-Step: How DCF Works

Let’s break down the DCF process step by step. While the basic idea is simple—discount future cash flows—the details are where things get interesting.

### Step 1: Estimate Future Cash Flows

The first step in any DCF model is to estimate the company’s **future cash flows**. This is where the art comes in, because you have to make assumptions about how the company will perform over the next several years.

For public companies, you can start with historical financials and analyst estimates to project future revenue, expenses, and profits. But for private companies, this can be trickier, since you won’t have the same level of transparency or historical data. In either case, the goal is to estimate the company’s **free cash flow**—the cash that’s left over after all operating expenses and capital expenditures have been paid. This is the cash that’s available to investors, so it’s the cash that matters for valuation.

Typically, you’ll project cash flows for 5-10 years, depending on how far into the future you think you can reasonably forecast. For most companies, it’s hard to predict anything beyond 10 years with any accuracy, so that’s usually the upper limit.

### Step 2: Choose a Discount Rate

Once you’ve estimated the future cash flows, you need to choose a **discount rate**. The discount rate reflects the risk of the company. The riskier the company, the higher the discount rate should be. A high discount rate means future cash flows are worth less today, while a low discount rate means future cash flows are worth more.

For public companies, the discount rate is usually based on the company’s **cost of capital**. The most common approach is to use the **Weighted Average Cost of Capital (WACC)**, which is a blend of the company’s cost of equity and cost of debt. Equity is riskier than debt, so it has a higher cost. By combining the cost of equity and the cost of debt, you get a discount rate that reflects the overall risk of the company.

For private companies, estimating the discount rate is harder because you don’t have as much information about the company’s capital structure or market risk. One practical approach is to use the discount rate of a comparable public company in the same industry, adjusted for the specific risks of the private company. For example, a startup in a volatile industry might have a higher discount rate than a mature company in the same industry, because the startup is riskier.

### Step 3: Calculate the Terminal Value

The next step is to calculate the **terminal value**—the value of the company beyond the projection period. Most DCF models only estimate cash flows for 5-10 years, but companies are expected to keep generating cash flows beyond that. The terminal value captures the value of all those future cash flows beyond the forecast period.

There are two common ways to calculate the terminal value:

1. **Perpetuity Growth Method**: This method assumes that the company’s cash flows will continue to grow at a constant rate forever. The formula for the terminal value is:
    
     $\text{Terminal Value} = \frac{\text{Final Year’s Cash Flow} \times (1 + \text{Growth Rate})}{\text{Discount Rate} - \text{Growth Rate}}$
    
    The growth rate is usually small, reflecting long-term economic growth (often between 2-3%).
    
2. **Exit Multiple Method**: This method assumes the company will be sold at the end of the forecast period for some multiple of its cash flows or earnings. You can use industry averages or comparable company data to estimate the exit multiple. For example, if companies in the same industry typically sell for 10 times earnings, you can apply that multiple to the company’s final year of earnings to calculate the terminal value.
    

Both methods have their pros and cons, but the perpetuity growth method is more common because it’s based on the intrinsic value of the company’s cash flows, rather than relying on external market conditions.

### Step 4: Discount the Cash Flows to the Present

Once you’ve estimated the future cash flows and the terminal value, the next step is to **discount** them back to the present. This is where the math comes in. The formula for discounting a cash flow is:

$\text{Present Value of Cash Flow} = \frac{\text{Future Cash Flow}}{(1 + \text{Discount Rate})^n}$

where $n$ is the number of years in the future. You apply this formula to each year’s cash flow and the terminal value, then sum them up to get the total **present value** of the company’s future cash flows.

### Step 5: Adjust for Debt and Cash

Finally, once you’ve calculated the present value of the company’s future cash flows, you need to adjust for debt and cash to get the company’s **equity value**. If the company has debt, you subtract it from the present value of the cash flows, because debt holders have a claim on the company’s assets. If the company has cash, you add it, because cash is an asset that belongs to the equity holders.

The result is the company’s **equity value**—the value of the company’s shares. For public companies, you can compare this equity value to the current market price to see whether the stock is overvalued or undervalued. For private companies, this equity value gives you an estimate of what the company is worth in an acquisition or investment.

## DCF for Public Companies

So how does DCF work in practice for public companies? The process is relatively straightforward because you have access to a wealth of information—historical financials, analyst estimates, market data, and the company’s capital structure. You can use this information to build a detailed model of the company’s future cash flows and choose a discount rate that reflects the company’s risk.

One of the biggest challenges with public companies is that they’re subject to market forces that can affect their value in unpredictable ways. For example, a company might have strong fundamentals, but its stock price could be depressed because of broader market volatility or investor sentiment. In these cases, DCF can be a useful tool because it allows you to focus on the **intrinsic value** of the company, rather than the fluctuations of the stock market.

However, DCF isn’t perfect for public companies. One of the criticisms is that it’s very sensitive to small changes in assumptions. If you change the discount rate by just 1%, it can have a big impact on the final valuation. The same goes for growth assumptions—if you’re too optimistic or too conservative, the DCF model can give you a misleading result. That’s why it’s important to use DCF as one tool among many when valuing public companies. It’s not a crystal ball, but it’s a powerful way to think about value.

## DCF for Private Companies

DCF for private companies is a different beast altogether. Unlike public companies, private companies don’t have an active market for their shares, and they often don’t have the same level of financial transparency. This makes it much harder to estimate future cash flows and choose a discount rate.

One of the biggest challenges with private companies is that they’re often much more volatile and uncertain than public companies. A startup, for example, might have huge growth potential, but it’s also much riskier because it doesn’t have a proven track record. As a result, the discount rate for private companies is usually higher to reflect the additional risk. Investors in private companies demand a higher return to compensate for the fact that the company is less liquid and more uncertain.

Another challenge with private companies is that they often have less predictable cash flows. A public company might have stable revenue and earnings, but a private company—especially a startup—might have wildly fluctuating cash flows, or even negative cash flows for several years. In these cases, you have to make more aggressive assumptions about future growth and profitability, which introduces more uncertainty into the DCF model.

One practical approach for valuing private companies with DCF is to use **scenario analysis**. Rather than building a single DCF model with one set of assumptions, you can create multiple scenarios based on different growth and risk assumptions. For example, you might build a “best case” scenario where the company grows rapidly and achieves profitability in a few years, and a “worst case” scenario where growth is slower, and the company takes longer to become profitable. By comparing the results of these different scenarios, you can get a better sense of the range of possible outcomes and the risks involved.

## The Limits of DCF: What It Can’t Tell You

As powerful as DCF is, it has its limits. One of the biggest limitations is that it relies on a lot of assumptions—about future cash flows, growth rates, and discount rates. Small changes in these assumptions can have a big impact on the final valuation. For example, if you’re valuing a company with a discount rate of 10%, and you increase the discount rate to 11%, the value of the company could drop by 10% or more. The same goes for growth assumptions—if you’re too optimistic about the company’s growth prospects, you could end up overvaluing the company.

Another limitation of DCF is that it doesn’t take into account **market sentiment**. A company might have strong fundamentals and a high intrinsic value, but if the market is bearish or investors are pessimistic, the stock price could remain depressed for a long time. DCF is a tool for valuing the intrinsic cash flows of a company, but it doesn’t tell you much about how the market will behave.

Finally, DCF doesn’t account for **unexpected events**. Companies operate in a complex, ever-changing world, and things like economic downturns, regulatory changes, or even technological disruption can have a big impact on a company’s future cash flows. DCF assumes that the future will unfold in a relatively predictable way, but the reality is often much messier.

## Conclusion: DCF as a Way of Thinking

At the end of the day, DCF is more than just a formula for valuing companies—it’s a way of thinking about value, time, and risk. It forces you to make explicit assumptions about how a company will perform in the future, and it gives you a framework for understanding how those assumptions affect the company’s value today.

But DCF is also a tool with limitations. It’s sensitive to small changes in assumptions, and it doesn’t account for market sentiment or unexpected events. That’s why it’s important to use DCF as one part of a broader toolkit for valuing companies. It’s not a crystal ball, but it’s a powerful way to think clearly about what a company is worth, and how its value is shaped by time and risk.

For public companies, DCF allows you to cut through the noise of the stock market and focus on the company’s intrinsic value. For private companies, DCF gives you a way to think about the future in a structured, disciplined way, even when there’s a lot of uncertainty. In either case, the value of DCF comes not just from the final number, but from the process of thinking carefully about what drives a company’s value.
