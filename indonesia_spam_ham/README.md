# Indonesia Spam Ham

Contains spam and ham Indonesian words (mixed with English words). Raw dataset. It was compiled from:
- https://www.kaggle.com/datasets/raflyahmadzainur/spam-dataset-indonesia
- https://www.kaggle.com/datasets/bobsteward/dataset-sms-spam-indonesia
- https://www.kaggle.com/datasets/gevabriel/indonesian-sms-spam
- https://archive.ics.uci.edu/dataset/228/sms+spam+collection
- Previous "indonesia_online_gambling" dataset

How to load:
```python
import pandas as pd

url = "https://raw.githubusercontent.com/RifqiAnshariR/useful-datasets/refs/heads/master/indonesia_spam_ham/indonesia_spam_ham.csv"

df = pd.read_csv(url)
print(df.head())