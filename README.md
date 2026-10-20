# Quantitative Finance Master Guides

### Unified Master Guides — From First Principles to Practice

> **Don't just learn the formulas. See the architecture behind them.**

Quantitative Finance Master Guides is a growing, openly shared collection of independently rewritten, self-contained guides to quantitative finance. Each guide reconstructs a subject around its **fundamental questions, mathematical dependencies, and practical applications**—not the conventional chapter order of a textbook or lecture syllabus.

The result is a different way to learn: **rigorous enough to understand the mathematics, concise enough to navigate, and practical enough to build on in a quantitative finance career.**

## The philosophy: rebuild the logic

A topic is easier to understand when you know why it exists, what assumptions it needs, how its mathematics follows, and where it fits into the broader field.

This collection follows five principles:

1. **First principles before formulas.** Start from the economic or statistical problem, then develop the mathematical solution.
2. **Logical dependencies before conventional chapter order.** Move concepts when doing so reveals a clearer intellectual structure.
3. **Intuition alongside rigor.** Connect the economic meaning, the equations, and the derivations.
4. **One coherent framework per field.** Treat models and techniques as parts of a connected system rather than an inventory of unrelated tools.
5. **Career-oriented depth without unnecessary length.** Aim for substantial coverage within each guide's scope, without turning the material into a slide transcription or an exam cramming sheet.

**The order may be unconventional. The logic should not be.**

## The guide library

| Subject | Guide | PDF |
| :-- | :-- | :-- |
| **Poisson, Exponential, Gamma & Beta** | *A Unified Framework for Counts, Waiting Times, Order Statistics, and Probability Inference* | **[Read PDF](./guides/Poisson_Exponential_Gamma_Beta_Unified_Guide.pdf)** |
| **Conditioning, Generating Functions & Gaussian Methods** | *Conditional Probability, Expectation, Variance, and Normal Distributions* | **[Read PDF](./guides/Contidion_GF_Gaussian.pdf)** |
| **Fixed Income** | *A Unified Framework for Pricing, Term Structure, Risk, and Markets* | **[Read PDF](./guides/Fixed_Income.pdf)** |
| **Financial Data Science** | *A Unified Modeling Framework* | **[Read PDF](./guides/Financial_Data_Science.pdf)** |
| **Investments** | *A Quantitative Finance Master Guide* | **[Read PDF](./guides/Investments.pdf)** |
| **Options & Greeks** | *An Interview-Oriented Mathematical and Economic Guide* | **[Read PDF](./guides/Options_Greeks_Master_Guide.pdf)** |

### Poisson, Exponential, Gamma & Beta

**The conceptual map**

`Poisson Counts → Exponential Waits → Gamma/Erlang Arrival Times → Inspection Paradox → Beta & Order Statistics → Gamma Ratios → Bayesian Updating & Prediction`

Builds a unified probability framework by asking what is random: a count, a waiting time, a position, a proportion, or an unknown probability. Starting from Poisson processes, the guide derives Exponential and Gamma waiting-time laws through equivalent events, then connects Beta distributions to order statistics, same-rate Gamma ratios, Bayesian inference, Beta–Binomial prediction, and common quantitative-finance interview problems.

**[Open the Poisson, Exponential, Gamma & Beta guide →](./guides/Poisson_Exponential_Gamma_Beta_Unified_Guide.pdf)**

### Conditioning, Generating Functions & Gaussian Methods

**The conceptual map**

`Joint Model → Condition → Aggregate → PGF/MGF/CGF → Random Sums → Gaussian Moments → Projection → Multivariate Signals`

Develops a unified toolkit for computing probabilities, predicting means, and quantifying risk under partial information. The guide moves from conditional distributions, continuous Bayes, total expectation, and total variance to probability-, moment-, and cumulant-generating functions; it then applies those tools to random sums, normal moments, Gaussian conditioning, orthogonal projection, multivariate normal models, signal extraction, and quantitative-finance interview problems.

**[Open the Conditioning, Generating Functions & Gaussian Methods guide →](./guides/Contidion_GF_Gaussian.pdf)**


### Fixed Income

**The conceptual map**

`No-Arbitrage → Discounting → Term Structure → Rate Dynamics → Pricing → Instruments → Risk → Hedging → Markets`

Starts from the law of one price and valuation of dated cash flows, then develops yield curves, stochastic-rate frameworks, fixed-income securities and derivatives, duration and convexity, key-rate and multifactor risk, portfolio hedging, and real market conventions.

**[Open the Fixed Income guide →](./guides/Fixed_Income.pdf)**

### Financial Data Science

**The conceptual map**

`Model → Fit → Uncertainty → Diagnose → Select → Repair → Predict`

Organizes regression, least squares, maximum likelihood, uncertainty quantification, model evaluation, diagnostics, and financial time-series modeling as successive decisions in a unified statistical workflow, connecting mathematical theory with financial applications.

**[Open the Financial Data Science guide →](./guides/Financial_Data_Science.pdf)**

### Investment

**The conceptual map:**

`Investment Problem → Returns & Risk → Economic Valuation (SDF) → Expected Returns & Risk Forecasting → Portfolio Optimization → Asset Pricing & Factor Models → Robust Construction → Implementation → Performance Evaluation`

Develops investment theory from the fundamental problem of allocating capital under uncertainty. Beginning with return measurement, risk preferences, no-arbitrage, and the stochastic discount factor, the guide builds a unified framework connecting expected-return prediction, covariance estimation, portfolio optimization, CAPM, multifactor asset pricing, and systematic investment strategies. It then extends the theoretical framework to estimation uncertainty, portfolio constraints, active management, performance attribution, and market efficiency—linking financial economics to practical quantitative investment research.

**[Open the Investments guide →](./guides/Investments.pdf)**

### Options & Greeks

**The conceptual map**

`Payoff → Distribution → Price → Derivatives → Hedge → P&L`

Builds option intuition from terminal payoffs and no-arbitrage pricing through the Black–Scholes–Merton model and its full sensitivity surface. The guide derives and interprets delta, gamma, vega, theta, rho, and higher-order Greeks; connects moneyness, maturity, implied volatility, and realized volatility to hedging and P&L; and closes with practical frameworks, worked problems, and common traps for quantitative-finance interviews.

**[Open the Options & Greeks guide →](./guides/Options_Greeks_Master_Guide.pdf)**


## Who this is for

For students and practitioners preparing for or working in **quantitative trading, quantitative research, financial engineering, risk management, and systematic investing**, and anyone who wants to understand *why* financial models work, not merely how to apply their formulas.

Read a guide sequentially to build the full framework, or return to an individual section as a technical reference. This is a growing collection, not a claim to cover every area of quantitative finance yet.

## About the author

### Mizuki Seika

I'm **Mizuki Seika**, a **quantitative trader** working at the intersection of mathematics, financial markets, and emerging technology; an explorer of **Web3 and cryptocurrency**; and, in a parallel universe that happens to be equally real, an **independent idol and original music producer**.

My academic path spans **Carnegie Mellon University's Master of Science in Computational Finance (MSCF '28)**, **Mathematics at Tsinghua University ('25)**, and an **exchange year at the University of Oxford ('24)**. My interests range from quantitative research and systematic trading to decentralized finance and digital assets.

To me, markets and music have more in common than they appear to: both reward an ear for signals, a sense of structure, and the courage to build something original. **In finance, I turn complexity into models. In music, I turn it into melodies.** This repository is where I bring that same creative discipline to learning—reconstructing knowledge until the pieces form a framework that actually makes sense.

**Explore my worlds:**

- **[LinkedIn](https://www.linkedin.com/in/mizukiseika0318)** — Quantitative finance, research, and technology
- **[CMU MSCF profile](https://www.cmu.edu/mscf/people/meet-our-students/golden-guo)** — Academic and professional background
- **[GitHub](https://github.com/GxLenesky)** — Open-source projects, quantitative finance guides, and research
- **[Instagram](https://www.instagram.com/mizukiseika0318/)** — The creative side, on and off stage
- **[Spotify](https://open.spotify.com/artist/1HEckzvLoXU4D5X9JDAMUg)** — Original music

## Feedback and contributions

Found a mistake, a missing link between concepts, or a clearer derivation? Open an **Issue** with the guide title and section. Constructive feedback is welcome.

The guides are independently rewritten educational materials; they should not be interpreted as investment recommendations. Unless a separate license is provided, no open-content reuse license is granted merely by making the repository public.

## License

© 2026 Mizuki Seika.

The original educational materials in this repository are licensed under the [Creative Commons Attribution 4.0 International License (CC BY 4.0)](LICENSE).

You are free to share and adapt these materials, including for commercial purposes, provided that appropriate credit is given to the author, the license is linked, and any changes are indicated.

---

*Learn the logic. Build the intuition. Apply the mathematics.*

