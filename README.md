# 星野宇潮 / Ushio Hoshino

公認会計士・税理士。自律型AIエージェントを現実の産業に社会実装しています。

CPA & Tax Accountant based in Tokyo. I build autonomous AI agents for real-world industries — bringing the discipline of financial audit into the age of AI.

- 株式会社インベーダーズ 創業者・取締役 CFO / Founder, Director & CFO, INVADERS Inc.
- メタワークス会計事務所・コンサルティング 代表
- 一般社団法人RULEMAKERS DAO 監事
- 公認会計士登録番号 **42168**（[日本公認会計士協会の公認会計士等検索システム](https://registry.jicpa.or.jp/cpa_search/ms_search?reg_code=42168&search=1)で照会できます）

## 🖋 右筆 / Yuhitsu

**監査人向けのAI監査支援ツール。判断と署名は監査人に残す。**

会計データから法人様式の監査調書を下書きまで自動生成し、開示チェックと証憑突合まで端末内で完結します（生データを外に出しません）。公認会計士本人が設計・実証しています。

An AI audit-support tool for auditors. It drafts audit working papers from accounting data, checks disclosures and matches vouchers — all on-device, so raw data never leaves the browser. Judgment and sign-off stay with the auditor.

→ https://invaders.co.jp/yuhitsu/

## 無料で試せる会計ツール

やりたい作業の行から、入手先と使い方を選んでください。6製品の用途と、起動に必要な環境をまとめました。

架空データで照合や利益と現金の計算を試すには、[会計AI検証室](https://www.invaders.co.jp/lab/hoshino-cpa-lab/)を開いてください。入力条件・処理結果・出典も確認できます。自分の資料を扱う製品は、下の表から選べます。

| やりたい作業 | ツール | 必要な環境 | 入手先・使い方 |
|---|---|---|---|
| 帳簿と請求の対応を確認し、判断を保存する | [月次照合](https://github.com/USHIKUNDESUYO/monthly-reconcile) | ChromeまたはEdge | [入手先](https://github.com/USHIKUNDESUYO/monthly-reconcile/releases/tag/v0.1.0-preview.20261014-guides.1)・[使い方](https://github.com/USHIKUNDESUYO/monthly-reconcile/blob/main/GUIDE.md) |
| 監査調書の下書き・開示チェック・CSV照合・OCRを使う | [YUHITSU全機能無料版](https://github.com/USHIKUNDESUYO/yuhitsu-free) | Windows 10/11の64ビットPC | [入手先](https://github.com/USHIKUNDESUYO/yuhitsu-free/releases/tag/v0.1.8-free.20261014)・[使い方](https://invaders.co.jp/yuhitsu/guide/) |
| 仕訳データを一次スクリーニングする | [shiwake-mcp](https://github.com/USHIKUNDESUYO/shiwake-mcp) | Node.js 20以上。AIツールから使う場合はMCP接続 | [入手先](https://www.npmjs.com/package/shiwake-mcp/v/0.3.1)・[使い方](https://github.com/USHIKUNDESUYO/shiwake-mcp/blob/ee39b6c51c50e4b5ff68ea09a10645db315c5310/README.md) |
| 架空データで支払利息の差を確かめる | [監査利息デモ](https://github.com/USHIKUNDESUYO/audit-interest-demo) | Python 3.10以上（標準ライブラリ） | [入手先](https://github.com/USHIKUNDESUYO/audit-interest-demo/releases/tag/v0.1.1-preview.20261013-input.1)・[使い方](https://github.com/USHIKUNDESUYO/audit-interest-demo/blob/v0.1.1-preview.20261013-input.1/README.md) |
| 見本の取引を分類し、仕訳を確認・保存する | [Jev会計の無料プレビュー](https://github.com/USHIKUNDESUYO/jev-kaikei-free) | Python 3.10以上とブラウザー。まずモックで試す | [入手先](https://github.com/USHIKUNDESUYO/jev-kaikei-free/releases/tag/v0.1.0-preview.20261013-saved-review.1)・[使い方](https://github.com/USHIKUNDESUYO/jev-kaikei-free/blob/v0.1.0-preview.20261013-saved-review.1/README.md) |
| 保存済みの評価JSONを集計する | [証憑研究版の評価JSON集計ツール](https://github.com/USHIKUNDESUYO/shohyo-metrics-source) | Python 3.10以上（標準ライブラリ） | [入手先](https://github.com/USHIKUNDESUYO/shohyo-metrics-source/releases/tag/v0.1.3-source-preview.20261013)・[使い方](https://github.com/USHIKUNDESUYO/shohyo-metrics-source/blob/v0.1.3-source-preview.20261013/README.md) |

月次照合・shiwake-mcp・監査利息デモ・Jev会計・証憑研究版の集計ツールはMITライセンスです。同梱の著作権表示と許諾文を残して、利用・改変・再配布できます。YUHITSU全機能無料版は個人・法人の業務で無料利用できますが、本体の改変・販売・再配布はこの配布版の[利用条件](https://github.com/USHIKUNDESUYO/yuhitsu-free/blob/bf63b64ed3c218ab14002c71f93bf781bd36d226/LICENSE.txt)では許諾されていません。第三者のソフトウェアには、それぞれのライセンスが適用されます。

shiwake-mcpは、AIツールから呼び出すための接続方式MCPに対応します。監査利息デモは教材、証憑研究版の集計ツールは研究用です。Jev会計のモックでは外部APIを使いません。ライブAPIを使う場合は、別途契約と費用の確認が必要です。各製品の案内で、出力の範囲と利用者が確認する箇所を確かめてください。

配布版・入手先・利用条件・作者は、[JSON一覧](./software.json)にもまとめています。

## 🏯 SEKISHO（関所）

**AIは承認しない。反証だけを返すデプロイの関所。**

An AI deployment gate where agents never approve — they only return refutations. Humans judge every refutation, and a SHA-256 hash-chained "passage permit" opens the GitHub Actions gate.

→ [USHIKUNDESUYO/sekisho](https://github.com/USHIKUNDESUYO/sekisho)（Findy DevOps × AI Agent Hackathon 2026 応募作品）

## Links

- プロフィール（正本） / Profile: https://invaders.co.jp/members/hoshino-ushio.html
- English profile: https://invaders.co.jp/en/members/hoshino-ushio.html
- メタワークス会計事務所・コンサルティング: https://metaworksgroup.jp/u-hoshino
- 株式会社インベーダーズ: https://invaders.co.jp/
- note: https://note.com/ushikun_desu
- LinkedIn: https://www.linkedin.com/in/ushiohoshino/
- Wikidata: [Q140668335](https://www.wikidata.org/wiki/Q140668335)
