# 高等学校化学・化学基礎 学習アプリポータル

## 概要

高等学校化学・化学基礎の学習用Webアプリをまとめて、生徒が1つのページからアクセスできるようにするためのポータルサイトです。

各学習アプリは独立したGitHubリポジトリで管理し、このポータルではそれぞれのGitHub Pagesへリンクします。

## 掲載アプリ

学習内容を「概念理解」「計算練習」で分けるのではなく、**教科・分野を中心に整理**しています。

### 化学基礎

- **mol計算**

### 化学

#### 電池・電気分解

- **電池の概念**
- **電気分解概念**
- **電池・電気分解の量的関係**

#### 気体

- **概念**
- **計算**

## 利用方法

ポータルページから利用したい学習アプリを選択してください。

各アプリはGitHub Pagesで公開されているため、ブラウザから直接利用できます。

## 構成

このリポジトリは、個々の学習アプリを格納するのではなく、**学習アプリへの入口を提供するポータル**として運用します。

```text
chem_apps/
├── index.html
└── README.md
```

個々のアプリはそれぞれ独立したリポジトリで管理します。

```text
chem_app_concept_gas-laws
chem_app_concept_battery
chem_app_concept_electrolysis
chem_app_calc_mol
chem_app_calc_electrochem
chem_app_calc_gas-laws
```

## 技術構成

- HTML
- CSS
- GitHub Pages
- 各学習アプリへの外部リンク

ポータル自体は単一の `index.html` で構成し、外部JavaScriptフレームワークには依存しません。

## バージョン

現在のバージョン：**v1.0.0**

## 更新情報（リリースノート）

### v1.0.0 — 2026-08-15

- 初回リリース
- 高等学校化学・化学基礎の学習アプリを一覧表示するポータルを実装
- 「化学基礎」「化学」の教科構成に沿ってアプリを分類
- 「電池・電気分解」「気体」の分野別にアプリを整理
- 6つの学習用Webアプリへのリンクを実装
- GitHub Pagesで各アプリへ直接アクセスできる構成を実装
- スマートフォン・タブレット・PCで利用できるレスポンシブなUIを実装

## 関連リポジトリ

- [chem_app_concept_gas-laws](https://github.com/k2ka3711/chem_app_concept_gas-laws)
- [chem_app_concept_battery](https://github.com/k2ka3711/chem_app_concept_battery)
- [chem_app_concept_electrolysis](https://github.com/k2ka3711/chem_app_concept_electrolysis)
- [chem_app_calc_mol](https://github.com/k2ka3711/chem_app_calc_mol)
- [chem_app_calc_electrochem](https://github.com/k2ka3711/chem_app_calc_electrochem)
- [chem_app_calc_gas-laws](https://github.com/k2ka3711/chem_app_calc_gas-laws)

## ライセンス

このリポジトリの利用条件については、今後必要に応じて設定します。
