# AUDUSD 15m OHLCV Forex Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-349_210_rows-blue)](https://getdata.finance/datasets/audusd) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/audusd)

### -> [**Download the full AUDUSD dataset on getdata.finance**](https://getdata.finance/datasets/audusd)

**AUDUSD 15m OHLCV forex historical data** — ultra high-quality 15m OHLCV for **AUDUSD**. 24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

## Table of contents

- [Why this dataset?](#why-this-dataset)
- [Download sample CSV](#download-sample)
- [GitHub Pages preview](#github-pages)
- [Sample vs full dataset](#sample-vs-full-dataset)
- [Timeframes on GetData](#timeframes-on-getdata)
- [Weekly updates](#weekly-updates)
- [Data preview](#data-preview)
- [Schema](#schema)
- [Code examples](#code-examples)
- [Download full data on getdata.finance](#download-full-data-on-getdata)

## Why this dataset?

- **Ultra high-quality 15m OHLCV** for **AUDUSD** (Forex)
- **24/5 market coverage — Asia, Europe and US sessions with institutional-style FX candles**
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`15m`) · **9 timeframes** on [getdata.finance](https://getdata.finance/datasets/audusd) · **349,210** `1m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `15m` sample updated in sync

> **Sample on GitHub** · `AUDUSD_15m.csv` (12,479 rows, `2026-02-01` -> `2026-07-31`). **Full archive on [getdata.finance](https://getdata.finance/datasets/audusd)** — **349,210** `1m` rows (~27.28 MB), **9 timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W), `2012-06-24` -> `2026-07-31`.

## Download sample

**[AUDUSD_15m.csv](https://github.com/getdata-finance/audusd-15m-ohlcv-forex-historical-data/blob/main/AUDUSD_15m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/audusd-15m-ohlcv-forex-historical-data/main/AUDUSD_15m.csv)) · [GitHub Releases](https://github.com/getdata-finance/audusd-15m-ohlcv-forex-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/audusd-15m-ohlcv-forex-historical-data/](https://getdata-finance.github.io/audusd-15m-ohlcv-forex-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/audusd](https://getdata.finance/datasets/audusd)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/audusd))** |
|---|--:|---|
| Instrument | AUDUSD · Forex | AUDUSD · Forex |
| Timeframes | `15m` (sample) | **9** — 1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W |
| 1m rows | 12,479 | **349,210** |
| Size | 1.28 MB | ~27.28 MB |
| Period | `2026-02-01` -> `2026-07-31` | `2012-06-24` -> `2026-07-31` |
| File | `AUDUSD_15m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/audusd) |
| Coverage report | — | [AUDUSD coverage](https://getdata.finance/coverage/audusd) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`15m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/audusd)**, each full asset archive is delivered as a ZIP with **9 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m** · **3m** · **5m** · **15m** · **30m** · **1H** · **12H** · **3D** · **1W**

GitHub = `15m` sample · [getdata.finance](https://getdata.finance/datasets/audusd) = all **9** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `15m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`AUDUSD_15m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-02-01T22:15:00+00:00 | 0.70132 | 0.70152 | 0.70095 | 0.70095 | 319.4526355087 |
| 2026-02-01T22:30:00+00:00 | 0.70095 | 0.70131 | 0.70074 | 0.70092 | 1183 |
| 2026-02-01T22:45:00+00:00 | 0.70092 | 0.70099 | 0.70029 | 0.70032 | 1358 |
| 2026-02-01T23:00:00+00:00 | 0.70032 | 0.70121 | 0.69895 | 0.69931 | 4005 |
| 2026-02-01T23:15:00+00:00 | 0.69931 | 0.69967 | 0.69841 | 0.69949 | 3937 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-07-31T19:45:00+00:00 | 0.7182 | 0.71827 | 0.71762 | 0.71762 | 1751 |
| 2026-07-31T20:00:00+00:00 | 0.71762 | 0.71773 | 0.71743 | 0.71772 | 1264 |
| 2026-07-31T20:15:00+00:00 | 0.71772 | 0.71805 | 0.71767 | 0.7179 | 1391 |
| 2026-07-31T20:30:00+00:00 | 0.7179 | 0.71816 | 0.71784 | 0.71805 | 1197 |
| 2026-07-31T20:45:00+00:00 | 0.71805 | 0.71828 | 0.71656 | 0.71662 | 1976 |

## Schema

| Column | Description |
| --- | --- |
| `datetime` | Bar open timestamp (UTC, ISO-8601). |
| `open` | Opening price of the candlestick bar. |
| `high` | Highest price during the bar. |
| `low` | Lowest price during the bar. |
| `close` | Closing price of the candlestick bar. |
| `volume` | Tick volume (number of price updates) during the bar. |

```text
datetime,open,high,low,close,volume
```

## Code examples

### pandas

```python
import pandas as pd

df = pd.read_csv('AUDUSD_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
print(df.resample('1h').agg({'open': 'first', 'high': 'max',
                              'low': 'min', 'close': 'last', 'volume': 'sum'}).head())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('AUDUSD_15m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)

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

df = pd.read_csv('AUDUSD_15m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='1min')
print(pf.stats())
```

## Download full data

The complete **AUDUSD** archive on **[getdata.finance](https://getdata.finance/datasets/audusd)** includes **9 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 12H · 3D · 1W) — **349,210** rows at `1m`, plus all other timeframes in the same ZIP.

**[-> Get the full AUDUSD dataset on getdata.finance](https://getdata.finance/datasets/audusd)**

---
*GetData · AUDUSD 15m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/audusd) · 2026-08-05 UTC*
