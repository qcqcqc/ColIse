# ColIse — Local QoE Analyzer

本仓库用于归档本地 QoE 分析工具源码。

## Current archived version

- **QoE Analyzer V2.0.4**
- Local Windows application with FastAPI + DuckDB + Parquet + browser UI
- Game / video QoE analysis
- Cable vs FTTH comparison (`FTTH = 100.109.192.0/18`)
- Busy-hour analysis
- Heavy-user and poor-QoE user identification
- FTTH migration opportunity scoring
- PON / OLT upgrade-priority analysis
- Chinese / English / Spanish UI
- Page-level and full-report HTML/PDF export

## Source archive

The clean source snapshot is stored under `archives/`.

The archive intentionally excludes local runtime and customer data:

- `.venv/`
- `runtime_data/`
- DuckDB / Parquet files
- logs
- local exports
- original XLSX / large source datasets

Sample CSV files inside the archive are synthetic/demo data only.

## Runtime requirements

- Windows
- Python 3.11 / 3.12 recommended
- FastAPI
- Uvicorn
- DuckDB 1.5.5
- PyArrow 25.0.1

See the README inside the source archive for startup and offline-install instructions.
