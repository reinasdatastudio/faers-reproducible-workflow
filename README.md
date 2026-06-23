# Reproducible Pharmacovigilance Workflow Using FAERS

![R](https://img.shields.io/badge/R-276DC3?logo=r&logoColor=white)
![Quarto](https://img.shields.io/badge/Quarto-39729E?logo=quarto&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-green)
![Healthcare](https://img.shields.io/badge/Healthcare-009688)
![Reproducible Workflow](https://img.shields.io/badge/Reproducible-Workflow-success)

Data files are not included.
Download the relevant quarterly files from the FDA website and place them in the data folder before rendering the report.

## Full report:
[Reproducible Pharmacovigilance Workflow Using FAERS](https://reinasdatastudio.github.io/faers-reproducible-workflow/FAERS2025Q3.html)

## Overview

This project demonstrates a reproducible workflow for exploratory pharmacovigilance analysis using the FDA Adverse Event Reporting System (FAERS) 2025 Q3 dataset.

Using the REAC and OUTC tables, the workflow explores adverse reaction reporting patterns, outcome severity, and case-level reporting behaviour while emphasising reproducible analysis and careful interpretation of spontaneous reporting data.

## Key Features

- Reproducible workflow using Quarto
- Case-level aggregation to reduce duplicate follow-up reports
- Exploratory analysis of REAC and OUTC tables
- Publication-quality visualisations using ggplot2
- Transparent and reproducible R workflow

## Technologies

- R
- tidyverse
- ggplot2
- Quarto

## Repository Structure

- FAERS2025Q3.qmd
- original-code.qmd
- README.md
- images/

## Disclaimer

FAERS is a spontaneous reporting database and should not be used to estimate incidence or establish causality. This project is intended for educational purposes and exploratory signal awareness.

## Author

Reina Kaino

Former Pharmacist | Data Scientist

Website:
https://reinasdatastudio.github.io/webpage/

&ensp;

---

&ensp;

# FAERSを用いた再現可能なファーマコビジランス解析ワークフローの構築

データファイルは本リポジトリには含まれていません。
レポートを実行する際は、FDAのWebサイトから対象四半期のデータファイルをダウンロードし、dataフォルダに配置してください。

## レポート
[FAERSを用いた再現可能なファーマコビジランス解析ワークフローの構築](https://reinasdatastudio.github.io/faers-reproducible-workflow/FAERS2025Q3.html)

## 概要

本プロジェクトでは、**FDA Adverse Event Reporting System（FAERS）2025年第3四半期（Q3）** の公開データを用いて、再現可能なファーマコビジランス解析ワークフローを構築しました。

REAC（副作用情報）およびOUTC（転帰情報）テーブルを用い、副作用報告の傾向や転帰の重症度について探索的解析を実施しています。臨床的なリスク評価や因果関係の推定を目的としたものではなく、再現可能なデータ解析手法と透明性の高いワークフローを示すことを目的としています。

## 主な内容

* Quartoを用いた再現可能な解析ワークフロー
* REAC・OUTCデータの前処理および統合
* 症例単位でのデータ集約による重複報告への対応
* 副作用報告パターンおよび転帰情報の探索的解析
* ggplot2による可視化

## 使用技術

* R
* tidyverse
* ggplot2
* Quarto

## ディレクトリ構成

- FAERS2025Q3.qmd
- original-code.qmd
- README.md
- images/

## 注意事項

FAERSは自発報告データベースであり、本解析結果から副作用の発生頻度や因果関係を判断することはできません。

本プロジェクトは、教育および再現可能な医療データ解析の実践例として作成しています。

## 作成者

**戒能 伶奈**

元薬剤師｜データサイエンティスト

R・医療データ解析・再現可能な解析ワークフローに興味があります。

**Website**
https://reinasdatastudio.github.io/webpage/
