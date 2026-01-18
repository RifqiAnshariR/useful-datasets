# slang_formal_dictionary

Dataset contains slang and formal Indonesian words. It was processed (remove missing values & duplicates, case folding, and trim white spaces), and compiled from:
- https://github.com/nasalsabila/kamus-alay
- https://github.com/ShinyQ/One-Click-Sentiment_BE
- https://github.com/lantip/baku-tidak-baku

How to load:
```python
import pandas as pd

df = pd.read_csv('dataset.csv')
print(df.head())