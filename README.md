# INTC 3d OHLCV US stocks Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-1_498_rows-blue)](https://getdata.finance/datasets/intc) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/intc)

### -> [**Download the full INTC dataset on getdata.finance**](https://getdata.finance/datasets/intc)

**INTC 3d OHLCV stocks historical data** — ultra high-quality 3d OHLCV for **Intel**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3d OHLCV** for **Intel** (US stocks)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3d`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/intc) · **1,498** `3d` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3d` sample updated in sync

> **Sample on GitHub** · `INTC_3d.csv` (244 rows, `2024-09-14` -> `2026-09-25`, 22.62 KB). **Full archive on [getdata.finance](https://getdata.finance/datasets/intc)** — **1,498** `3d` rows (full `1m`: 634,759), **11 timeframes**, `2011-05-08` -> `2026-09-25`.

## Download sample

**[INTC_3d.csv](https://github.com/getdata-finance/intc-3d-ohlcv-stocks-historical-data/blob/main/INTC_3d.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/intc-3d-ohlcv-stocks-historical-data/main/INTC_3d.csv)) · [GitHub Releases](https://github.com/getdata-finance/intc-3d-ohlcv-stocks-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/intc-3d-ohlcv-stocks-historical-data/](https://getdata-finance.github.io/intc-3d-ohlcv-stocks-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/intc](https://getdata.finance/datasets/intc)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/intc))** |
|---|--:|---|
| Instrument | Intel · US stocks | Intel · US stocks |
| Timeframes | `3d` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3d rows | 244 | **1,498** |
| Size | 22.62 KB | full ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Period | `2024-09-14` -> `2026-09-25` | `2011-05-08` -> `2026-09-25` |
| File | `INTC_3d.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/intc) |
| Coverage report | — | [INTC coverage](https://getdata.finance/coverage/intc) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3d` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/intc)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3d` sample · [getdata.finance](https://getdata.finance/datasets/intc) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3d` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`INTC_3d.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2024-09-14T00:00:00+00:00 | 19.61 | 21.02 | 19.61 | 20.88 | 9862 |
| 2024-09-17T00:00:00+00:00 | 20.88 | 22.53 | 20.67 | 21.12 | 42459 |
| 2024-09-20T00:00:00+00:00 | 21.12 | 23.06 | 20.3 | 21.83 | 18024 |
| 2024-09-23T00:00:00+00:00 | 21.83 | 23.99 | 21.83 | 23.5 | 34501 |
| 2024-09-26T00:00:00+00:00 | 23.5 | 24.59 | 23.18 | 23.84 | 23572 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-13T00:00:00+00:00 | 102.91 | 102.91 | 94.45 | 97.04 | 152401 |
| 2026-09-16T00:00:00+00:00 | 97.04 | 111.31 | 97.04 | 108.61 | 255464 |
| 2026-09-19T00:00:00+00:00 | 108.61 | 124.66 | 108.61 | 121.8 | 106431 |
| 2026-09-22T00:00:00+00:00 | 121.8 | 127.38 | 119.37 | 127.28 | 304710 |
| 2026-09-25T00:00:00+00:00 | 127.28 | 127.28 | 122.77 | 122.83 | 106308 |

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

df = pd.read_csv('INTC_3d.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('INTC_3d.csv', parse_dates=['datetime'])
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

df = pd.read_csv('INTC_3d.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3d')
print(pf.stats())
```

## Download full data

The complete **INTC** archive on **[getdata.finance](https://getdata.finance/datasets/intc)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **1,498** rows at `3d`, plus all other timeframes in the same ZIP.

**[-> Get the full INTC dataset on getdata.finance](https://getdata.finance/datasets/intc)**

---
*GetData · INTC 3d OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/intc)*
