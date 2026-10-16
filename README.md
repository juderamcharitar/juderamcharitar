<div align="center">

# Jude Kriel Ramcharitar

**QUANTITATIVE RESEARCH · MARKET MICROSTRUCTURE · APPLIED MACHINE LEARNING**

Carnegie Mellon University · Business Administration, AI in Business · 2029

*I turn market questions into measurable experiments — from order-book data to out-of-sample evaluation.*

[Research paper](https://github.com/juderamcharitar/latency-compensating-mm/blob/main/paper_v4/main.pdf) · [Research code](https://github.com/juderamcharitar/latency-compensating-mm) · [Portfolio ↗](https://jude-ramcharitar.netlify.app/) · [Contact](mailto:j.k.ramcharitar@gmail.com)

</div>

---

## Flagship research

### [How Much Does Limit Order Book Microstructure Add Beyond Quote Geometry?](https://github.com/juderamcharitar/latency-compensating-mm)

**Independent working paper · 2026**

Can order-book signals predict simulated limit-price crossings **beyond what quote placement already tells us**?

<div align="center">

| 269,330 | 3 markets | 63 features |
| :---: | :---: | :---: |
| Timestamped 10-level book snapshots | BTC/USD · ETH/USD · SOL/USD | Microstructure features in the reported GBT comparison |

</div>

**Out-of-sample results — improvement in AUC over a quote-geometry lookup baseline**

| Market | Blocked split | Forecasting-ordered temporal split |
| :--- | ---: | ---: |
| **BTC/USD** | **+0.048** | **+0.048** |
| **ETH/USD** | **+0.049** | **+0.060** |
| **SOL/USD** | **+0.027** | Negative; result does not generalize |

The study compares **gradient-boosted trees and LSTM models** with a simple quote-geometry baseline and includes corrected label construction, leakage audits, pre-experiment verification, and robustness tests.

> **Scope of the result:** The label measures a replay-defined *quote crossing*, not a verified trade fill, net trading P&L, or executable strategy. Earlier versions contained pipeline defects; the current paper documents their correction.

**[Paper (PDF) →](https://github.com/juderamcharitar/latency-compensating-mm/blob/main/paper_v4/main.pdf)** · **[Source code →](https://github.com/juderamcharitar/latency-compensating-mm)** · **[Reproduction guide →](https://github.com/juderamcharitar/latency-compensating-mm#reproducing)**

---

## How I approach quant research

```text
MARKET QUESTION
      │
      ▼
DATA + ASSUMPTIONS
      │
      ▼
SIMPLE BASELINE ──► FEATURE ENGINEERING
      │                      │
      └──────────┬───────────┘
                 ▼
          MODEL COMPARISON
                 │
                 ▼
      TEMPORAL / BLOCKED TESTS
                 │
                 ▼
     LEAKAGE + ROBUSTNESS CHECKS
                 │
                 ▼
       REPRODUCIBLE FINDINGS
```

I care about **what a model learns, whether the signal survives realistic evaluation, and where the result breaks down**.

## Beyond the order book

| Focus | What I work on |
| :--- | :--- |
| **Quantitative trading research** | Limit-order-book modeling, execution-oriented questions, financial time series, and backtesting methodology |
| **Artificial intelligence** | Feature engineering, predictive modeling, machine-learning experiments, and research automation |
| **Business & consulting** | Entrepreneurship, analytical problem-solving, financial decisions, and translating technical ideas into useful systems |
| **Software** | Python research workflows and web products built with TypeScript, React, and Next.js |

### [Explore my personal portfolio ↗](https://jude-ramcharitar.netlify.app/)

Financial research, AI, entrepreneurship, and software projects in one place.

## Tools & methods

**Programming:** `Python` · `TypeScript` · `JavaScript`  
**Research:** `Gradient-Boosted Trees` · `LSTM` · `Feature Engineering` · `Time-Series Validation`  
**Engineering:** `Data Pipelines` · `Model Diagnostics` · `Git` · `Reproducible Experiments`  
**Product:** `React` · `Next.js` · `Tailwind CSS`

---

<div align="center">

**Interested in quantitative trading, market microstructure, AI, and research-driven decision-making.**

[Website](https://jude-ramcharitar.netlify.app/) · [Email](mailto:j.k.ramcharitar@gmail.com) · [ORCID](https://orcid.org/0009-0004-8190-1958)

</div>
