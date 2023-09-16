---
########### THIS FILE IS AUTO GENERATED - ANY CHANGES WILL BE VOID ###########
title: summaryflow
description: OpenBB Telegram Command
---

# summaryflow

This command allows the user to retrieve a summary of all the flow per stock over the last x days, with the result sorted in various ways. This summary will include the ratio to total market capitalization, the number of trades, and other information.

### Usage

```python wordwrap
/summaryflow days sort
```

---

## Parameters

| Name | Description | Optional | Choices |
| ---- | ----------- | -------- | ------- |
| days | Number of days to look back | False | None |
| sort | Sort by `mc` (MarketCap), `float`, `sum`, or `short` (Short Percentage) | False | mc, float, sum, short |


---

## Examples

```
/summaryflow 1 float
```

```
/summaryflow 1 sum
```
---
