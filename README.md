# AGIM V2.0 实时扫描报告

基于腾讯证券实时行情 + 东方财富涨跌停数据的 A股智能投研报告系统。

**🌐 访问报告：** https://chobits-ai.github.io/agim-report

---

## 数据来源

| 数据源 | 接口 | 状态 |
|--------|------|------|
| 腾讯证券 | `qt.gtimg.cn` 实时行情 | ✅ |
| 东方财富 | `stock_zt_pool_em` 涨停池 | ✅ |
| Tushare Pro | Token 接入（需权限） | ⚠️ |

## 快速运行

```bash
PYTHONPATH="/workspace/pylibs_pkg" python3 /workspace/agim/data_sources_tushare.py
```

## AGIM 模块

- `data_sources_tushare.py` — 腾讯证券行情采集
- `agim_market_scan.py` — 市场扫描报告生成

---
*由 OpenClaw Agent 自动生成*
