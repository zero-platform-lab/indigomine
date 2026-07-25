# Indigomine

**Redmine 6.x** 向けのインディゴ（青紫）テーマ。[Bleuclair](https://github.com/farend/redmine_theme_farend_bleuclair)（GPLv2）をベースに、配色をインディゴ化しモダンに調整した派生テーマです。

*Read this in [English](README.en.md).*

ビルド不要。コンパイル済みの CSS/JS を同梱しているので、`themes/` に置くだけで使えます。

## Bleuclair からの変更点

- **インディゴ／青紫の配色** — ヘッダのグラデーション、リンク、アクセントカラー。
- **ラベンダーのハイライト** — 薄黄色だったホバー／ボックス／カード背景を置き換え。
- **本文の色みを調整** — 純黒ではなく、ほんのり紫みのある濃色（`#342e56`）。
- **項目名（ラベル）を強調** — チケット詳細の項目名を太字＋インディゴ（`#453a80`）、値は普通の文字。
- **トラッカー色のチケット ID タグ** — 一覧のチケット ID をトラッカーごとにインディゴ系で色分け。
- **2 段の「ピッカー」チップ** — チケット詳細タイトル（トラッカー＋番号）を右尖りのリボン形に（同梱の `javascripts/theme.js` で処理）。
- **モダンなフォントスタック**（BIZ UDPGothic / system-ui）、角丸カード、淡い罫線、行ホバー。
- **Simple Gantt** プラグインが CSS 変数（`--sg-*`）経由でテーマ配色に追従。

## インストール（Redmine 6.x）

1. Redmine の `themes/` ディレクトリにクローン：

   ```bash
   cd /path/to/redmine/themes
   git clone https://github.com/zero-platform-lab/indigomine.git
   ```

2. Redmine を再起動（Propshaft が起動時にテーマアセットを再生成します）。
3. **管理 → 設定 → 表示 → テーマ → Indigomine → 保存**。

## ライセンスとクレジット

Bleuclair から継承した **GNU General Public License v2.0（GPLv2）** で配布します。
[`LICENSE`](LICENSE) と [`NOTICE`](NOTICE) を参照してください。

- オリジナルテーマ：**Bleuclair**（Far End Technologies / farend）
- 配色・レイアウトの改変：zero-platform-lab
- アップストリーム（SCSS ソースを含む）：<https://github.com/farend/redmine_theme_farend_bleuclair>
