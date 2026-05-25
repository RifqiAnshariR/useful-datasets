# Indonesia Slang Formal

Contains slang and formal Indonesian words. It was processed (remove missing values & duplicates, case folding, and trim white spaces), and compiled from:
- https://github.com/nasalsabila/kamus-alay
- https://github.com/ShinyQ/One-Click-Sentiment_BE
- https://github.com/lantip/baku-tidak-baku

How to load:
```python
import pandas as pd

url = "https://raw.githubusercontent.com/RifqiAnshariR/useful-datasets/refs/heads/master/indonesia_slang_formal/indonesia_slang_formal.csv"

df = pd.read_csv(url)
print(df.head())