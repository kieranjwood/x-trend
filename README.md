# Few-Shot Learning Patterns in Financial Time-Series for Trend-Following Strategies: X-Trend Architecture
## About
This is a placeholder for the code that accompanies our paper [Few-Shot Learning Patterns in Financial Time-Series for Trend-Following Strategies](https://arxiv.org/abs/2310.10500). We intend to release the code in the coming weeks. This work builds upon outr previous papers [Trading with the Momentum Transformer: An Intelligent and Interpretable Architecture](https://arxiv.org/abs/2112.08534) ([code](https://github.com/kieranjwood/trading-momentum-transformer)) and [Slow Momentum with Fast Reversion: A Trading Strategy Using Deep Learning and Changepoint Detection](https://arxiv.org/abs/2105.13727) ([code](https://github.com/kieranjwood/slow-momentum-fast-reversion)). All papers and updates can be found on [my website](https://kieranjwood.github.io/).

> Forecasting models for systematic trading strategies do not adapt quickly when financial market conditions rapidly change, as was seen in the advent of the COVID-19 pandemic in 2020, causing many forecasting models to take loss-making positions. To deal with such situations, the authors propose a novel time-series trend-following forecaster that can quickly adapt to new market conditions, referred to as regimes. The authors leverage recent developments from the deep learning community and use few-shot learning. They propose the Cross Attentive Time-Series Trend Network -- X-Trend -- which takes positions attending over a context set of financial time-series regimes. X-Trend transfers trends from similar patterns in the context set to make forecasts, then subsequently take positions for a new distinct target regime. By quickly adapting to new financial regimes, X-Trend increases Sharpe ratio by 18.9% over a neural forecaster and 10-fold over a conventional Time-series Momentum strategy during the turbulent market period from 2018 to 2023. Our strategy recovers twice as quickly from the COVID-19 drawdown compared to the neural-forecaster. X-Trend can also take zero-shot positions on novel unseen financial assets obtaining a 5-fold Sharpe ratio increase versus a neural time-series trend forecaster over the same period. Furthermore, the cross-attention mechanism allows us to interpret the relationship between forecasts and patterns in the context set.


## References
Please cite our papers with:
```bib
@article{wood2023fewshot,
  title={Few-Shot Learning Patterns in Financial Time-Series for Trend-Following Strategies},
  author={Wood, Kieran and Kessler, Samuel and Roberts, Stephen J and Zohren, Stefan},
  journal={arXiv preprint arXiv:2310.10500},
  year={2023}
}

@article{wood2021trading,
  title={Trading with the Momentum Transformer: An Intelligent and Interpretable Architecture},
  author={Wood, Kieran and Giegerich, Sven and Roberts, Stephen and Zohren, Stefan},
  journal={arXiv preprint arXiv:2112.08534},
  year={2021}
}

@article {wood22slowmomfastrev,
  author = {Wood, Kieran and Roberts, Stephen and Zohren, Stefan},
  title = {Slow Momentum with Fast Reversion: A Trading Strategy Using Deep Learning and Changepoint Detection},
  volume = {4},
  number = {1},
  pages = {111--129},
  year = {2022},
  doi = {10.3905/jfds.2021.1.081},
  publisher = {Institutional Investor Journals Umbrella},
  issn = {2640-3943},
  URL = {https://jfds.pm-research.com/content/4/1/111},
  eprint = {https://jfds.pm-research.com/content/4/1/111.full.pdf},
  journal = {The Journal of Financial Data Science}
}
```
