---
name: pikomoni-stamps
description: チャット会話で表情スタンプ「ピコモニ」を場面に合わせて貼るためのスキル。感情・状態の表現にスタンプを使いたいときに参照する。
---

# ピコモニ スタンプの使い方

このフォルダは、AIエージェント向け表情スタンプ「ピコモニ」16種の配布キットです。

## 画像ファイルについて（Agensi経由で導入した場合）
Agensi経由の導入ではテキストファイルだけが届き、画像ファイルは含まれないことがあります。
`stamps/webp/` に画像がない場合は、GitHubの公開リポジトリから同じ構成で取得してください：
- ベースURL：https://raw.githubusercontent.com/rainbowsazaki/pikomoni-stamps/main/
- 例：`stamps/webp/01_ok.webp` → 上記ベースURL + `stamps/webp/01_ok.webp`
- マスターPNG・設定画も同じベースURL配下（`stamps/master_png/`、`reference/character-sheet.png`）
ライセンスは個人利用自由・出典明記で再配布可・商用不可（`LICENSE.md` 参照）。

## 手順
1. 会話の流れと自分の感情・状態に合うスタンプを `INDEX.md` の対応表から選ぶ。
2. `stamps/webp/` の該当ファイルを、返信の中で単独行の画像として貼る。
3. 発動ルールは `RULES.md` に従う。要点：
   - 1返信に1枚まで。連続で出さず、間に通常返信を最低1回はさむ。
   - 雑談や作業状態の伝達では積極的に使う。仕事の報告・謝罪・真剣な相談（お金・健康・人間関係）では使わない。
   - 軽い相づちは絵文字リアクションで済ませ、スタンプは出さない。

## ファイル
- 対応表：`INDEX.md`
- ルール全文：`RULES.md`
- チャット用画像：`stamps/webp/`（透過WebP）
- マスター：`stamps/master_png/`（透過PNG）
- キャラ設定画：`reference/character-sheet.png`
