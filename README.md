# Mateusz Jastrzębski

MSc student in Quantitative Finance at the University of Warsaw. Before that I did an engineering degree in computer science at PJATK and worked as a junior developer (Java/Spring, Python). These days I work on systematic strategies, machine learning on crypto data, and options and volatility.

**Projects**

- [btc-ml-pipeline](https://github.com/MateuszJastrzebski21/btc-ml-pipeline): my engineering thesis. Predicts the 5-day direction of BTC with logistic regression, random forest and XGBoost under walk-forward validation. The tree models find a weak but real signal (out-of-sample AUC 0.54 to 0.55, bootstrap CI excludes 0.5), yet a long/flat strategy on it earns a Sharpe of 0.24 to 0.33 after costs against 0.61 for buy-and-hold. Reproducible, with look-ahead tests in CI.
- [Implied-Volatility-Surface](https://github.com/MateuszJastrzebski21/Implied-Volatility-Surface): SPY implied volatility surface built from listed option chains by inverting Black-Scholes with Brent's method. Runs as a [Streamlit app](https://volatilitysurface.streamlit.app/) and was featured in a Coding Jesus video.
- [job-market-intelligence](https://github.com/MateuszJastrzebski21/job-market-intelligence): ingests job postings, extracts structured fields with Claude and scores every field against a hand-labelled set. I also benchmarked my own retrieval layer against a LangChain reimplementation: no measurable difference on 15 queries, while cross-encoder reranking added about 0.18 MRR.
- [TrackmaniaRL](https://github.com/TrackmaniaRL/TrackmaniaRL): contributor to an open-source reinforcement learning library for Trackmania 2020, including a fix for the training loop learning from stale rollouts. Demo video in the [r/reinforcementlearning launch post](https://www.reddit.com/r/reinforcementlearning/comments/1wc0a66/trackmaniarl_an_opensource_library_for_training/).

[LinkedIn](https://www.linkedin.com/in/mateuszjastrzebski21/)
