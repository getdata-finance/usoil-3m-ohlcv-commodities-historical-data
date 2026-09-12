# USOIL 3m OHLCV Commodities Historical Data — Free Sample

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE) [![Dataset rows](https://img.shields.io/badge/full_dataset-2_025_812_rows-blue)](https://getdata.finance/datasets/usoil) [![Updated](https://img.shields.io/badge/weekly_update-every_Saturday_8am_UTC-green)](https://getdata.finance) [![Full data on getdata.finance](https://img.shields.io/badge/download-getdata.finance-orange)](https://getdata.finance/datasets/usoil)

### -> [**Download the full USOIL dataset on getdata.finance**](https://getdata.finance/datasets/usoil)

**USOIL 3m OHLCV commodities historical data** — ultra high-quality 3m OHLCV for **WTI Crude Oil**. Clean `datetime, open, high, low, close, volume` CSV for backtesting, algorithmic trading and quantitative research.

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

- **Ultra high-quality 3m OHLCV** for **WTI Crude Oil** (Commodities)
- **Clean CSV schema** — `datetime, open, high, low, close, volume` (no gaps in formatting)
- **Free evaluation sample** on GitHub (`3m`) · **11 timeframes** on [getdata.finance](https://getdata.finance/datasets/usoil) · **2,025,812** `3m` rows in the full archive
- Built for **backtesting**, **algorithmic trading** and **quantitative finance** workflows
- **Weekly refresh** — [getdata.finance](https://getdata.finance) every **Saturday, 8am UTC+0**; GitHub `3m` sample updated in sync

> **Sample on GitHub** · `USOIL_3m.csv` (59,794 rows, `2026-03-12` -> `2026-09-11`, 3.82 MB). **Full archive on [getdata.finance](https://getdata.finance/datasets/usoil)** — **2,025,812** `3m` rows (full `1m`: 5,981,180), **11 timeframes**, `2008-09-10` -> `2026-09-11`.

## Download sample

**[USOIL_3m.csv](https://github.com/getdata-finance/usoil-3m-ohlcv-commodities-historical-data/blob/main/USOIL_3m.csv)** on GitHub ([raw CSV](https://raw.githubusercontent.com/getdata-finance/usoil-3m-ohlcv-commodities-historical-data/main/USOIL_3m.csv)) · [GitHub Releases](https://github.com/getdata-finance/usoil-3m-ohlcv-commodities-historical-data/releases)

## GitHub Pages

Interactive chart & stats: **[https://getdata-finance.github.io/usoil-3m-ohlcv-commodities-historical-data/](https://getdata-finance.github.io/usoil-3m-ohlcv-commodities-historical-data/)**

Full archive & live chart on getdata.finance: **[https://getdata.finance/datasets/usoil](https://getdata.finance/datasets/usoil)**

## Sample vs full dataset

| | **Sample (this repo)** | **Full dataset ([getdata.finance](https://getdata.finance/datasets/usoil))** |
|---|--:|---|
| Instrument | WTI Crude Oil · Commodities | WTI Crude Oil · Commodities |
| Timeframes | `3m` (sample) | **11** — 1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W |
| 3m rows | 59,794 | **2,025,812** |
| Size | 3.82 MB | full ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Period | `2026-03-12` -> `2026-09-11` | `2008-09-10` -> `2026-09-11` |
| File | `USOIL_3m.csv` | ZIP on [getdata.finance](https://getdata.finance/datasets/usoil) |
| Coverage report | — | [USOIL coverage](https://getdata.finance/coverage/usoil) |
| Updates | Weekly (Saturday, 8am UTC+0) — GitHub sample | Weekly (Saturday, 8am UTC+0) — all timeframes |

## Timeframes on GetData

This GitHub repository ships a **`3m` evaluation sample** only. On **[getdata.finance](https://getdata.finance/datasets/usoil)**, each full asset archive is delivered as a ZIP with **11 gap-free OHLCV timeframes** (one CSV per timeframe):

**1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W**

GitHub = `3m` sample · [getdata.finance](https://getdata.finance/datasets/usoil) = all **11** timeframes above for the same instrument.

## Weekly updates

- **[getdata.finance](https://getdata.finance)** — Full datasets are updated every Saturday, 8am UTC+0.
- **GitHub (this repo)** — GitHub samples are refreshed weekly (every Saturday, 8am UTC+0), in sync with getdata.finance.

When a new `3m` sample is published on GitHub, the README, chart preview and CSV reflect the latest week of data.

## Data preview

First and latest rows from the GitHub sample **`USOIL_3m.csv`**:

**First rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-03-12T02:30:00+00:00 | 93.619 | 94.223 | 93.619 | 94.208 | 818 |
| 2026-03-12T02:33:00+00:00 | 94.208 | 94.858 | 94.122 | 94.834 | 1129 |
| 2026-03-12T02:36:00+00:00 | 94.834 | 95.938 | 94.662 | 95.392 | 1478 |
| 2026-03-12T02:39:00+00:00 | 95.392 | 95.402 | 94.843 | 94.992 | 1141 |
| 2026-03-12T02:42:00+00:00 | 94.992 | 95.069 | 94.684 | 94.939 | 963 |

**Last rows**

| datetime | open | high | low | close | volume |
| --- | --- | --- | --- | --- | --- |
| 2026-09-11T20:30:00+00:00 | 100.274 | 100.379 | 100.248 | 100.344 | 209 |
| 2026-09-11T20:33:00+00:00 | 100.344 | 100.364 | 100.217 | 100.282 | 164 |
| 2026-09-11T20:36:00+00:00 | 100.282 | 100.334 | 100.277 | 100.278 | 285 |
| 2026-09-11T20:39:00+00:00 | 100.278 | 100.304 | 100.252 | 100.268 | 180 |
| 2026-09-11T20:42:00+00:00 | 100.268 | 100.309 | 100.244 | 100.289 | 146 |

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

df = pd.read_csv('USOIL_3m.csv', parse_dates=['datetime'])
df.set_index('datetime', inplace=True)
print(df.describe())
```

### backtrader

```python
import backtrader as bt
import pandas as pd

df = pd.read_csv('USOIL_3m.csv', parse_dates=['datetime'])
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

df = pd.read_csv('USOIL_3m.csv', parse_dates=['datetime'])
close = df.set_index('datetime')['close']
fast, slow = vbt.MA.run(close, 10), vbt.MA.run(close, 50)
entries = fast.ma_crossed_above(slow)
exits = fast.ma_crossed_below(slow)
pf = vbt.Portfolio.from_signals(close, entries, exits, init_cash=10_000, freq='3min')
print(pf.stats())
```

## Download full data

The complete **USOIL** archive on **[getdata.finance](https://getdata.finance/datasets/usoil)** includes **11 OHLCV timeframes** (1m · 3m · 5m · 15m · 30m · 1H · 4H · 12H · 1D · 3D · 1W) — **2,025,812** rows at `3m`, plus all other timeframes in the same ZIP.

**[-> Get the full USOIL dataset on getdata.finance](https://getdata.finance/datasets/usoil)**

---
*GetData · USOIL 3m OHLCV sample on GitHub · Full historical data on [getdata.finance](https://getdata.finance/datasets/usoil)*
