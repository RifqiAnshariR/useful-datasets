# Indonesia Online Gambling

Contains raw Indonesia YouTube comments gathered from:
- https://www.youtube.com/channel/UCZQPLQgLMMDMVviAM68AHIQ

How to load:
```python
import pandas as pd

url = "https://raw.githubusercontent.com/RifqiAnshariR/useful-datasets/refs/heads/master/indonesia_online_gambling/indonesia_online_gambling.csv"

df = pd.read_csv(url)
print(df.head())