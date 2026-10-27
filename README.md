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
- **電気分解の概念**
- **電池・電気分解の量的関係**

#### 状態変化

- **気液平衡・蒸気圧・沸騰**

#### 気体

- **気体の法則 ― 概念**
- **混合気体の概念**
- **理想気体と実在気体**
- **気液平衡の概念 ― グラフで読む**
- **気体の法則 ― 計算**

#### 溶液

- **希薄溶液の性質の概念**

## 利用方法

ポータルページから利用したい学習アプリを選択してください。

各カードの「前提」は、そのアプリを使う前に学習しておきたい内容です。ポータル内の別のアプリが前提になる場合は、そのアプリ名を「」で示しています。

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
chem_app_concept_gas-mixtures
chem_app_concept_ideal-vs-real-gas
chem_app_concept_vapor-liquid-equilibrium
chem_app_concept_vapor-liquid-equilibrium-basic
chem_app_concept_colligative-properties
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

現在のバージョン：**v1.6.0**

## 更新情報（リリースノート）

### v1.6.0 — 2026-10-27

- 全カードに「前提」（そのアプリの前に学習しておきたい内容）を追加
- ポータル内の別のアプリが前提になる場合は、アプリ名を「」で示し、学ぶ順をたどれるようにした
- ページ冒頭の説明に「前提」の意味を追記

### v1.5.0 — 2026-10-27

- **理想気体と実在気体**（分子モデル・圧縮率因子 *Z*・ファンデルワールスの状態方程式）学習アプリをポータルに追加
- 「化学」→「気体」の項目に「理想気体と実在気体」を追加（「混合気体の概念」の次）
- 全カードの説明文を各アプリの実際の内容に合わせて見直し（扱う電池の種類、5分野の計算など）
- 「気液平衡の概念」を「気液平衡の概念 ― グラフで読む」に改め、「気液平衡・蒸気圧・沸騰」との違いが分かるようにした（「理想気体と実在気体」の次へ移動）
- 「計算」のアプリのラベルの色を変え、概念理解のアプリと見分けやすくした
- 「アプリを開く」ボタンに、読み上げ用のアプリ名（aria-label）を付けた
- 2026-08-19 に削除したお知らせ（各アプリの README の案内）が、v1.2.1 の更新で再び表示されていたので削除
- 新規アプリのGitHub Pagesへのリンクを実装
- 掲載アプリ一覧および関連リポジトリ一覧を更新

### v1.4.0 — 2026-09-29

- **混合気体の概念**（ドルトンの分圧の法則・連結容器シミュレーター）学習アプリをポータルに追加
- 「化学」→「気体」の項目に「混合気体の概念」を追加
- 新規アプリのGitHub Pagesへのリンクを実装
- 掲載アプリ一覧および関連リポジトリ一覧を更新

### v1.3.0 — 2026-09-13

- **気液平衡・蒸気圧・沸騰**の概念理解学習アプリをポータルに追加
- 「化学」→「状態変化」の分野を新設
- 「電池・電気分解」と「気体」の間に「状態変化」を配置
- 新規アプリのGitHub Pagesへのリンクを実装
- 掲載アプリ一覧および関連リポジトリ一覧を更新

### v1.2.1 — 2026-08-27

- 「希薄溶液の性質の概念」を「化学」→「気体」から移動
- 新たに「化学」→「溶液」の分野を追加
- 「溶液」配下に「希薄溶液の性質の概念」を配置
- ポータルの分類を実際の化学分野に合わせて整理

### v1.2.0 — 2026-08-27

- **希薄溶液の性質の概念理解**学習アプリをポータルに追加
- 「化学」→「気体」の項目に「希薄溶液の性質の概念」を追加
- GitHub Pagesへのリンクを実装
- 掲載アプリ一覧および関連リポジトリ一覧を更新

### v1.1.0 — 2026-08-19

- **気液平衡の概念理解**学習アプリをポータルに追加
- 「化学」→「気体」の項目に「気液平衡の概念」を追加
- GitHub Pagesへのリンクを実装
- 掲載アプリ一覧および関連リポジトリ一覧を更新

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
- [chem_app_concept_gas-mixtures](https://github.com/k2ka3711/chem_app_concept_gas-mixtures)
- [chem_app_concept_ideal-vs-real-gas](https://github.com/k2ka3711/chem_app_concept_ideal-vs-real-gas)
- [chem_app_concept_vapor-liquid-equilibrium](https://github.com/k2ka3711/chem_app_concept_vapor-liquid-equilibrium)
- [chem_app_concept_vapor-liquid-equilibrium-basic](https://github.com/k2ka3711/chem_app_concept_vapor-liquid-equilibrium-basic)
- [chem_app_concept_colligative-properties](https://github.com/k2ka3711/chem_app_concept_colligative-properties)
- [chem_app_concept_battery](https://github.com/k2ka3711/chem_app_concept_battery)
- [chem_app_concept_electrolysis](https://github.com/k2ka3711/chem_app_concept_electrolysis)
- [chem_app_calc_mol](https://github.com/k2ka3711/chem_app_calc_mol)
- [chem_app_calc_electrochem](https://github.com/k2ka3711/chem_app_calc_electrochem)
- [chem_app_calc_gas-laws](https://github.com/k2ka3711/chem_app_calc_gas-laws)

## ライセンス

このリポジトリの利用条件については、今後必要に応じて設定します。
