# Temporal Convolutional Networks & Knowledge Graphs

Temporal Convolutional Networks, or simply TCN, is a variation of Convolutional Neural Networks for sequence modelling tasks, by combining aspects of RNN and CNN architectures. Preliminary empirical evaluations of TCNs have shown that a simple convolutional architecture outperforms canonical recurrent networks such as LSTMs across a diverse range of tasks and datasets while demonstrating longer effective memory.

### Componenets

- Time-series Price Data: The price dataset of daily value records of DJIA index
- Textual News Data: News dataset composed of historical news headlines from Reddit WorldNews Channel (top 25 posts based on votes).
- Structured Knowledge Data: A sub-graph constructed from the structured data of two commonly used open knowledge graphs for research — Freebase and the Wikidata.

### Instructions

```
git clone git@github.com:james-sorrell/tcn.git
cd tcn
pip install -r requirements.txt
```

Plotly JupyterLab Support (Python 3.5+)

> https://plotly.com/python/getting-started/

### Links

> https://towardsdatascience.com/farewell-rnns-welcome-tcns-dd76674707c8
> https://github.com/philipperemy/keras-tcn