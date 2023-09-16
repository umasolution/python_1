---
########### THIS FILE IS AUTO GENERATED - ANY CHANGES WILL BE VOID ###########
title: hist
description: OpenBB Telegram Command
---

# hist

This command allows the user to retrieve the historical price of options for the given parameters of a ticker, expiry, strike , option type, and interval for the past x days in a chart format.

### Usage

```python wordwrap
/hist ticker expiry strike opt_type interval [past_days]
```

---

## Parameters

| Name | Description | Optional | Choices |
| ---- | ----------- | -------- | ------- |
| ticker | Stock Ticker | False | None |
| expiry | Expiration Date YYYY-MM-DD format | False | None |
| strike | Option Strike Price | False | None |
| opt_type | Calls or Puts (C or P) | False | calls, puts, C, P |
| interval | Chart Minute Interval. 15m, 30m, 1hr, 1d | False | 1d, 15m, 30m, 1hr |
| past_days | Past Days to Display. Default: 5 | True | None |


---

## Examples

```
/hist AMD 2022-07-29 70 Calls 15m 5
```

---
