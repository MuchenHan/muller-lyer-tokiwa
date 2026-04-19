# ミューラー・リヤー錯視実験（書籍準拠・調整法版）

常磐大学 心理学実験演習（31107000）用の jsPsych ベース錯視実験。
**『心理学実験演習』第 4 章（pp.17-25）に準拠した調整法・鋏角 3 水準 被験者内デザイン**（書籍の対面「実験者調整法」を web 単独実施に合わせ、被験者自身がスライダーを操作する「被験者調整法」に改変）。

## アクセス

GitHub Pages: <https://muchenhan.github.io/muller-lyer-tokiwa/>

## 実験仕様

| 項目 | 内容 |
|---|---|
| 独立変数 | 鋏角 15°/30°/60°（1 要因 3 水準 被験者内） |
| 測定法 | 被験者調整法（スライダー、被験者操作） |
| 従属変数 | 錯視量 = 内向主線長 − 外向主線長 (mm) |
| 試行数 | 24 試行（3 条件 × 8 試行：上昇 4／下降 4、標準左 4／右 4） |
| カウンターバランス | 6 順列、学籍番号末位 %6 で割当 |
| 鋏辺 | 30 mm 固定 |
| 標準刺激長 | 100 mm |

## 構成

- `index.html` — 方案A（書籍準拠）調整法 実験本体
- `legacy/muller_lyer_constant.html` — 旧恒常法版（参照専用、非公開）
- データ送信先: Google Apps Script → Google Sheet「muller_lyer_data_2026」
- Sheet 列: `timestamp, participant_id, permutation_index, method, order_index, condition_order, angle_deg, series, std_side, start_mm, response_mm, illusion_mm, rt_ms, user_agent`

## 授業期間

- 2026 年度 春学期（4/21 開始）
- 3 限・4 限合計 ~120 名

## 担当

韓 天一（han.tianyi624@gmail.com）
