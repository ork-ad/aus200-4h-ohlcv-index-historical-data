# AUS200 4h OHLCV Index Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_174_rows-blue)](https://ork.ad/) [![Updated](https://img.shields.io/badge/weekly_update-every_Sunday-green)](https://ork.ad/) [![Full data on ork.ad](https://img.shields.io/badge/download-ork.ad-orange)](https://ork.ad/)

### → [**Download the full AUS200 dataset on ork.ad**](https://ork.ad/)

**AUS200 4h OHLCV Stock index historical data** — ultra high-quality 4h OHLCV for **Australia 200 Index**. Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only. Clean `time, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on ork.ad](#timeframes-on-orkad)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on ork.ad](#download-full-data)

## Why this dataset?

- **Ultra high-quality 4h OHLCV** for **Australia 200 Index** (Stock index)
- **Global cash and extended index sessions — Asia, Europe and US coverage, not US-hours only**
- **Clean CSV schema** — `time, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`4h`) · **13 timeframes** on [ork.ad](https://ork.ad/) · **1,174** `4h` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [ork.ad](https://ork.ad/) every **Sunday**; GitHub `4h` sample updated in sync

> **Sample on GitHub** · `AUS200_4h.csv` (1,156 rows, `2025-10-02` → `2026-07-02`). **Full archive on [ork.ad](https://ork.ad/)** — **1,174** `4h` rows (~0.07 MB), **13 timeframes** (``1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W``), `2025-09-29` → `2026-07-02`.

## Download sample

**[AUS200_4h.csv](https://github.com/ork-ad/aus200-4h-ohlcv-index-historical-data/blob/main/AUS200_4h.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/ork-ad/aus200-4h-ohlcv-index-historical-data/main/AUS200_4h.csv)) · [GitHub Releases](https://github.com/ork-ad/aus200-4h-ohlcv-index-historical-data/releases) when the release workflow is active.

## GitHub Pages

Interactive chart & stats: **[https://ork-ad.github.io/aus200-4h-ohlcv-index-historical-data/](https://ork-ad.github.io/aus200-4h-ohlcv-index-historical-data/)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([ork.ad](https://ork.ad/))** |
|---|--:|---|
| Instrument | Australia 200 Index · Stock index | Australia 200 Index · Stock index |
| Timeframes | `4h` (sample) | **13** — `1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W` |
| 4h rows | 1,156 | **1,174** |
| Size | 0.07 MB | ~0.07 MB |
| Period | `2025-10-02` → `2026-07-02` | `2025-09-29` → `2026-07-02` |
| File | `AUS200_4h.csv` | ZIP on [ork.ad](https://ork.ad/) |
| Updates | Weekly (Sunday) — GitHub sample | Weekly (Sunday) — all timeframes |

## Timeframes on ork.ad

This GitHub repository ships a **`4h` evaluation sample** only. On **[ork.ad](https://ork.ad/)**, each full asset archive is delivered as a ZIP with **13 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **2H** · **4H** · **8H** · **12H** · **16H** · **1D** · **1W**

GitHub = `4h` sample · [ork.ad](https://ork.ad/) = all **13** timeframes above for the same instrument.

## Weekly updates

- **[ork.ad](https://ork.ad/)** — Full datasets on ork.ad are updated every Sunday.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Sunday), in sync with ork.ad.

When a new `4h` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUS200_4h.csv`**:

**First rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2025-10-02T20:00:00Z | 8932.049 | 8939.239 | 8930.029 | 8934.239 | 322.0 |
| 2025-10-03T00:00:00Z | 8934.239 | 8993.24 | 8925.239 | 8983.74 | 3373.0 |
| 2025-10-03T04:00:00Z | 8983.74 | 8997.24 | 8977.22 | 8988.23 | 1856.0 |
| 2025-10-03T08:00:00Z | 8988.23 | 9002.74 | 8984.24 | 8991.23 | 1179.0 |
| 2025-10-03T12:00:00Z | 8991.23 | 9046.73 | 8987.22 | 9035.22 | 3508.0 |

**Last rows**

| time | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| time | open | high | low | close | volume |
| 2026-07-02T04:00:00Z | 8727.31 | 8746.93 | 8711.81 | 8744.91 | 3703.0 |
| 2026-07-02T08:00:00Z | 8744.91 | 8772.93 | 8742.91 | 8758.43 | 2533.0 |
| 2026-07-02T12:00:00Z | 8758.43 | 8826.43 | 8755.42 | 8769.43 | 12780.0 |
| 2026-07-02T16:00:00Z | 8769.43 | 8780.43 | 8725.43 | 8777.43 | 6911.0 |

## Schema

```text
time,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUS200_4h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUS200_4h.csv', parse_dates=['time'])
df.set_index('time', inplace=True)

class PandasData(bt.feeds.PandasData):
    params = (('datetime', None), ('open', 'open'), ('high', 'high'),
              ('low', 'low'), ('close', 'close'), ('volume', 'volume'))

cerebro = bt.Cerebro()
cerebro.adddata(PandasData(dataname=df))
# cerebro.addstrategy(YourStrategy)
# cerebro.run()
```

### vectorbt

```python
import pandas as pd
import vectorbt as vbt

df = pd.read_csv('AUS200_4h.csv', parse_dates=['time'])
close = df.set_index('time')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='4h')
print(pf.stats())
```

## Download full data

The complete **AUS200** archive on **[ork.ad](https://ork.ad/)** includes **13 OHLCV timeframes** (`1m`, `3m`, `5m`, `15m`, `30m`, `1H`, `2H`, `4H`, `8H`, `12H`, `16H`, `1D`, `1W`) — **1,174** rows at `4h`, plus all other timeframes in the same ZIP.

**[→ Get the full AUS200 dataset on ork.ad](https://ork.ad/)**

---
*GetData · AUS200 4h OHLCV sample on GitHub · Full historical data on [ork.ad](https://ork.ad/) · 2026-07-04 UTC*