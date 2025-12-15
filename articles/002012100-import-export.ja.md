---
title: タスクのエクスポート・インポート
categoryId: how-to-use
subCategoryId: タスク管理
---

Repsona は、タスクを CSV 形式や Gantt-san 形式で、エクスポート・インポートすることができます。XLSX や PDF でのエクスポートにも対応しています。

| この機能を利用できる人 | この機能を利用できるプラン |
|-------------|---------------|
| すべて         | すべて           |

## サブメニューからエクスポート・インポート

タスク一覧やガントチャート画面のサブメニューから、エクスポート・インポートができます。

<img src="/images/help/sub-menu.png" width="36">

*↑ サブメニューボタン*

<img src="/images/help/import.ja.png" width="200">

## エクスポートする

CSV、Gantt-san JSON、XLSX、PDF でエクスポートすることができます。

### CSV エクスポート

「CSV エクスポート」を選択すると、CSV 形式でエクスポートすることができます。この形式は、Repsona にインポートできる CSV レイアウトです。

### Gantt-san エクスポート

「Gantt-san エクスポート」を選択すると、Gantt-san JSON 形式でエクスポートすることができます。Gantt-san にインポートして利用することできる形式です。

[ログインなしで無料で誰でも使えるガントチャート](https://repsona.com/ja/lp/free-gantt)

### XLSX エクスポート

「XLSX エクスポート」を選択すると、エクセル（Excel）で読み込み可能な形式でエクスポートすることができます。

### PDF エクスポート

「PDF エクスポート」を選択すると、印刷に適した形式でエクスポートすることができます。

## インポートする

CSV、Gantt-san JSON をインポートすることができます。

### CSV インポート

「CSV インポート」を選択すると、CSV 形式をインポートすることができます。

<a href="/files/task-sample.csv" target="_blank">サンプル CSV をダウンロード</a>

| カラム             | 論理名     | 説明                                               | 例                                                                                                                                                                                                          |
|-----------------|---------|--------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| id              | ID      | タスクを一意に定めるID。任意の文字列を指定できます。                      | 1                                                                                                                                                                                                          |
| name            | タスク名    | タスク名                                             | Agree budget                                                                                                                                                                                               |
| description     | タスクの説明  | タスクの説明                                           | It involves organizing estimated costs, breakdowns, and budget limits, then sharing them with relevant teams and decision-makers.If needed, adjustment options are proposed and final approval is secured. |
| responsibleUser | 担当者     | 担当者のユーザーネームを指定します。スペース内メンバーである必要があります。           | Reon                                                                                                                                                                                                       |
| ballHoldingUser | ボール保持者  | ボール保持者のユーザーネームを指定します。スペース内メンバーである必要があります。        | Seb                                                                                                                                                                                                        |
| startDate       | 開始日     | YYYY-MM-DD 形式で指定します。                             | 2024-01-01                                                                                                                                                                                                 |
| dueDate         | 期限日     | YYYY-MM-DD 形式で指定します。                             | 2024-12-31                                                                                                                                                                                                 |
| status          | ステータス   | タスクのステータスを指定します。プロジェクト内に存在するステータスである必要があります。     | Doing                                                                                                                                                                                                      |
| milestone       | マイルストーン | タスクのマイルストーンを指定します。プロジェクト内に存在するマイルストーンである必要があります。 | v1.37.0                                                                                                                                                                                                    |
| parent          | 親タスクID  | 親タスクIDを指定します。タスクのIDに指定したものを利用します。                | 4                                                                                                                                                                                                          |
| tags            | タグ      | タグをカンマ区切りで指定します。                                 | tag1,tag2                                                                                                                                                                                                  |
| planned         | 予定      | 予定工数等を指定します。自由単位です。                              | 5                                                                                                                                                                                                          |
| actual          | 実績      | 実績工数等を指定します。自由単位です。                              | 5                                                                                                                                                                                                          |
| sortOrder       | 表示順     | 一覧取り込み時の表示順を指定します。小さい値が上になります。                   | 1                                                                                                                                                                                                          |

### Gantt-san インポート

「Gantt-san インポート」を選択すると、Gantt-san JSON 形式をインポートすることができます。Gantt-san からエクスポートしたファイルを Repsona に取り込むことができます。

[Gantt-san から Repsona へのデータ移行 はこちらをご覧ください](004007000-gantt-san-json)
