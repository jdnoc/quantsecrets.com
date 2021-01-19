---
layout: post
title: Introduction to Quantitative Trading
description: The basics of quantitative trading, and how to get started.
date: 2021-01-19
---

**Here's the dream:** a fully automated cloud based trading system that knows exactly how to time the market and generate consistent profits.

Can that be a reality? *It depends*. But, the only way to get there is to learn all of the different facets of quantitative trading.

In this article, we'll talk about quantitative trading, including what it is and how it differs from traditional (speculative) trading. 

Over the next year (2021) Quant Secrets be outlining some key topics surrounding quantitative trading, including how to approach developing new trading algorithms, testing strategies, implementing strategies, and some of the skills required to make a complete live-trading system.

Let's get started.

## What is quant trading?

Quantitative (quant) trading is a form of trading that uses mathematical models (algorithms) to develop trading strategies and often execute market trades automatically. 

Quantitative trading algorithms are developed using a process called backtesting. To perform proper backtesting, historical data is obtained and models are tested (using walk forward optimization) to see how the model would have performed over time. 

For accurate models, real-word inefficiencies should be included, such as trade commissions, and slippage (the difference between the expected price of a trade and the price at which the trade is executed).

Automated trading systems (often on cloud servers) are used to create a complete system that retrieves new market data, determines if a trade should be made (based on algorithmic models) and makes a trade if necessary.

## Quant trading vs. Speculative trading

Unlike speculative trading (commonly referred to as "day trading"), quantitative trading is performed with little human interaction. 

Instead of relying on judgement, a quantitative trader relies on effective testing to develop new models, and the system would be able to capitalize on (or protect against) any major market changes.

As a speculative trader, you would need to be aware of market changes throughout the day, constantly looking at data and making decisions.

As a quantitative trader, your systems are watching market changes and making decisions for you, leaving you time to develop new algorithms and make long-term decisions about how to improve your portfolio.

## Quant trading vs. Algorithmic trading

Quantitative trading and algorithmic trading aren't necessarily different, but algorithmic trading is a subset of quantitative trading.

Quantitative trading is the process of developing trading models, and algorithmic trading is using those models to automatically trade in markets. Technically, once those models are produced, even a human could implement them manually.

Algorithmic trading expands on quantitative trading by not only creating trading models, but also developing systems that automatically trade on live markets.

## Pros and cons of quant trading

### Pros

Quantitative trading has many advantages over other forms of trading, as it lends itself to automation and requires less attention from the operator.

If an algorithm has been properly tested and has proven successful, there is little doubt it will perform well on the live market. This gives the operator assurance to continue developing new strategies to test and deploy.

With simple algorithms, it is easy to tweak and test new strategies from existing strategies. Therefore, the knowledge obtained can be compounded and many successful systems can be deployed simultaneously.

Through developing many systems (on the order of tens or hundreds of different strategies), one can hedge against major market changes and not lose their entire portfolio if one system performs poorly.

### Cons

The barrier to entry for quantitative trading is high. A quantitative trader would need to know the math, code, software, and processes for implementing strategies in order to configure a live-trading system.

Developing sound and proven tests on historical data is difficult, and is the true work of a quantitative trader. Once a successful algorithm is developed, it's not hard to implement (given the skills to do live trading via cloud servers).

Quantitative trading can be at a disadvantage when the market behaves erratically. Sometimes a system may be performing poorly, and it's not straightforward to completely understand why.