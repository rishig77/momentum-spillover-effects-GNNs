# Stock Movement Prediction Using Bi-typed Hybrid-relational Market Knowledge Graph and Dual Attention Networks

## Requirements
- Python 3.6.13
- Pytorch 1.7.1
- Geometric 1.7.2

## How to Run
```sh
$ python main1.py
```
- Ensure GPU is used to replicate experiments.

## Data
Datasets used for SMP:
- CSI100E
- CSI300E

### Selected Stocks
- CSI100E: `./raw_data/100E/stocks.txt`
- CSI300E: `./raw_data/300E/stocks.txt`

### Transactional Data
- Due to space limits, only part of the 1.1GB dataset is provided. More data and preprocessing code will be available soon.
- Partial data:
  - CSI100E: `./raw_data/100E/historical price.xlsx`
  - CSI300E: `./raw_data/300E/historical price.xlsx`

### Sentiment Indicators
- Only part of the 2.3GB news data is provided. More data and preprocessing code will be available soon.
- Partial financial news data:
  - CSI100E: `./raw_data/100E/financial news.xlsx`
  - CSI300E: `./raw_data/300E/financial news.xlsx`
- Sentiment extraction uses the finance-oriented sentiment dictionary: `./raw_data/sentiment_dictionary`.

### Inter-class Relations
- CSI100E: `./raw_data/100E/inter-class`
- CSI300E: `./raw_data/300E/inter-class`

### Intra-class Relations
- CSI100E: `./raw_data/100E/intra-class`
- CSI300E: `./raw_data/300E/intra-class`
