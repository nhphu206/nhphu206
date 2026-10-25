# Hi, I'm Nguyễn Hoài Phú 👋

Data Science student in Ho Chi Minh City, Vietnam. I build reproducible data and machine-learning
systems for scientific, geospatial and remote-sensing data.

## Featured project

### [Nha Be Radar–Himawari Forecasting Pipeline](https://github.com/nhphu206/nhabe-radar-himawari-portfolio)

An end-to-end research pipeline that aligns Nha Be weather-radar observations with five
Himawari-9 satellite bands, validates the generated dataset and evaluates controlled
deep-learning models for next-volume radar-reflectivity forecasting.

[![Project CI](https://github.com/nhphu206/nhabe-radar-himawari-portfolio/actions/workflows/ci.yml/badge.svg)](https://github.com/nhphu206/nhabe-radar-himawari-portfolio/actions/workflows/ci.yml)
[![Release](https://img.shields.io/github/v/release/nhphu206/nhabe-radar-himawari-portfolio?label=release)](https://github.com/nhphu206/nhabe-radar-himawari-portfolio/releases/tag/v1.0.0)

![Radar input, prediction, observation and error](https://raw.githubusercontent.com/nhphu206/nhabe-radar-himawari-portfolio/main/assets/portfolio/forecast_example.png)

| Verified result | Value |
| --- | ---: |
| Radar volumes inventoried | 8,916 |
| Aligned radar–satellite samples | 8,774 |
| Causally screened forecast pairs | 822 |
| Locked-test multimodal MAE / RMSE | 4.215 / 5.904 dBZ |
| RMSE reduction vs. persistence | 20.30% |

The public demonstration includes synthetic-data workflows, automated tests, Docker images,
Docker Compose, GitHub Actions and an offline FastAPI inference contract. Raw observations,
generated research datasets, trained checkpoints and personal reports are not published.

## Technology stack

**Data and scientific computing:** Python, NumPy, Py-ART, SatPy, Pyresample<br>
**Machine learning:** PyTorch, Small U-Net, masked regression metrics<br>
**Engineering:** FastAPI, Docker, Docker Compose, GitHub Actions, NPZ/JSON data contracts

## What I focus on

- reproducible scientific-data pipelines;
- spatial and temporal alignment across heterogeneous sensors;
- leakage-safe dataset construction and time-based evaluation;
- explicit missing-data masks instead of silently replacing missing values with zero;
- automated validation, provenance and honest reporting of limitations.

## Explore

- [Project overview and reproducible demo](https://github.com/nhphu206/nhabe-radar-himawari-portfolio)
- [End-to-end research release](https://github.com/nhphu206/nhabe-radar-himawari-portfolio/releases/tag/v1.0.0)
- [Continuous-integration runs](https://github.com/nhphu206/nhabe-radar-himawari-portfolio/actions)
