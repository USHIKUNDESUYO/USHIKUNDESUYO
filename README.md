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

- [月次照合](https://github.com/USHIKUNDESUYO/monthly-reconcile)：帳簿と請求のCSVから照合候補を出し、確認した判断を保存できます。ブラウザーで使うMITライセンスのツールです。[入手先](https://github.com/USHIKUNDESUYO/monthly-reconcile/releases/tag/v0.1.0-preview.20261011-guided.3)
- [YUHITSU全機能無料版](https://github.com/USHIKUNDESUYO/yuhitsu-free)：Windows向け。監査調書の下書き、開示チェック、CSV照合、OCRを利用できます。[使い方](https://invaders.co.jp/yuhitsu/guide/)と[利用条件](https://github.com/USHIKUNDESUYO/yuhitsu-free/blob/main/LICENSE.txt)を確認してください。
- [shiwake-mcp](https://github.com/USHIKUNDESUYO/shiwake-mcp)：仕訳をルールで一次スクリーニングします。AIツールから呼び出すための接続方式MCPに対応し、MITライセンスで公開しています。

- [監査利息デモ](https://github.com/USHIKUNDESUYO/audit-interest-demo)：架空データで支払利息の推定額と計上額の差を確かめる、MITライセンスの教材です。Pythonの標準ライブラリだけで動きます。 [入手先](https://github.com/USHIKUNDESUYO/audit-interest-demo/releases/tag/v0.1.1-preview.20261013-input.1)

- [Jev会計の無料プレビュー](https://github.com/USHIKUNDESUYO/jev-kaikei-free)：見本の取引を分類し、人が仕訳を確認してCSV・JSONへ保存できます。モックは外部APIを使わず動き、ソースはMITで再利用できます。[入手先](https://github.com/USHIKUNDESUYO/jev-kaikei-free/releases/tag/v0.1.0-preview.20261012-format.1)

- [証憑研究版の評価JSON集計ツール](https://github.com/USHIKUNDESUYO/shohyo-metrics-source)：保存済みJSONの率と正誤の入力形式を確認して集計する、MITの研究用ソースです。Python標準機能だけで動き、OCRとモデル重みは含みません。[入手先](https://github.com/USHIKUNDESUYO/shohyo-metrics-source/releases/tag/v0.1.1-source-preview.20261012)

6製品の確認版と入手先、利用条件、作者をまとめた[JSON一覧](./software.json)も公開しています。Jev会計の入手先は2026年10月12日の入力形式の確認版へ更新しました。証憑研究版の集計ツールも、同日の評価JSONの入力確認版へ更新しました。

監査利息デモの入手先は、2026年10月13日のJSON入力の確認版へ更新しました。

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
