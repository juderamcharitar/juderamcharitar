<div align="center">

# Jude Kriel Ramcharitar

### Quantitative Research · Market Microstructure · Applied AI

**Carnegie Mellon University** · Business Administration + AI in Business · Class of 2029

I build and study systems at the intersection of **financial markets, machine learning, and software** — with an emphasis on empirical rigor, reliable evaluation, and real-world decision-making.

[**Research paper**](https://github.com/juderamcharitar/latency-compensating-mm/blob/main/paper_v4/main.pdf) &nbsp;·&nbsp; [**Code**](https://github.com/juderamcharitar/latency-compensating-mm) &nbsp;·&nbsp; [**Portfolio**](https://jude-ramcharitar.netlify.app/) &nbsp;·&nbsp; [**Email**](mailto:j.k.ramcharitar@gmail.com)

</div>

---

## Featured quantitative research

### [How Much Does Limit Order Book Microstructure Add Beyond Quote Geometry?](https://github.com/juderamcharitar/latency-compensating-mm)

*Independent working paper · August 2026 · Cryptocurrency market microstructure*

**Research question:** Do limit-order-book features improve prediction of a simulated limit price being crossed, beyond the information already captured by quote offset, time horizon, and side?

| Research design | Detail |
| :-- | :-- |
| **Market data** | 269,330 timestamped, 10-level order-book snapshots from Kraken |
| **Assets** | BTC/USD · ETH/USD · SOL/USD |
| **Models** | Quote-geometry lookup baseline · gradient-boosted trees · LSTM |
| **Evaluation** | Blocked and forecasting-ordered temporal splits; leakage checks; robustness analysis |
| **Reproducibility** | Verification scripts, experiment code, reported results, and paper |

**Selected findings:** On a blocked split, gradient-boosted trees using 63 microstructure features improved AUC over the quote-geometry lookup baseline by **+0.048 (BTC), +0.049 (ETH), and +0.027 (SOL)**. On a forecasting-ordered temporal split, gains remained positive for BTC and ETH but **reversed on SOL**.

**Interpretation matters:** The target is a *replay-defined quote crossing*, **not an observed executed fill or a demonstrated profitable trading strategy**. The current paper also documents and corrects defects in earlier versions of the research.

[**Read the paper →**](https://github.com/juderamcharitar/latency-compensating-mm/blob/main/paper_v4/main.pdf) &nbsp; [**Examine the implementation →**](https://github.com/juderamcharitar/latency-compensating-mm) &nbsp; [**Reproduce the experiments →**](https://github.com/juderamcharitar/latency-compensating-mm#reproducing)

---

## What I'm focused on

| Quantitative finance | Artificial intelligence | Business & strategy |
| :-- | :-- | :-- |
| Market microstructure and order-book signals | Predictive modeling and feature engineering | Entrepreneurship and operating systems |
| Execution-aware research questions | Time-series evaluation and robustness | Financial analysis and decisions under uncertainty |
| Backtesting methodology and reproducibility | Research software and automation | Structured problem-solving and strategy |

My approach: **define the question → construct a defensible baseline → test out of sample → investigate failure cases → make the results reproducible.**

## Selected work

**[Limit Order Book Microstructure Research](https://github.com/juderamcharitar/latency-compensating-mm)**  
A public research repository containing data-processing and modeling pipelines, corrected labeling, verification scripts, robustness tests, and a working paper.

**[Personal Portfolio ↗](https://jude-ramcharitar.netlify.app/)**  
My website bringing together work across financial research, AI, entrepreneurship, and software. Built with Next.js, React, TypeScript, Tailwind CSS, and Motion.

## Technical toolkit

**Languages:** Python · TypeScript · JavaScript  
**Quant & ML:** Feature engineering · Gradient-boosted trees · LSTMs · Time-series validation · Model diagnostics  
**Research engineering:** Data pipelines · Backtesting methodology · Reproducible experiments · Git  
**Web & product:** React · Next.js · Tailwind CSS

---

## Connect

**Website:** [jude-ramcharitar.netlify.app](https://jude-ramcharitar.netlify.app/)  
**Email:** [j.k.ramcharitar@gmail.com](mailto:j.k.ramcharitar@gmail.com)  
**Research identifier:** [ORCID 0009-0004-8190-1958](https://orcid.org/0009-0004-8190-1958)

<sub>Interested in quantitative trading, market research, applied machine learning, and the intersection of technology and business.</sub>
