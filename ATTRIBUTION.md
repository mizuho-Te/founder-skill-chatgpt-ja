# 出典・ライセンス・変更点

## 原作

- Project: Founder Skill
- Author: Jake Schincariol
- Repository: https://github.com/Jakeschincariol/founder-skill
- License: MIT
- Copyright (c) 2026 Jake Schincariol
- 参照コミット: `fd9385b0cfe1b96bebce3898fbd506d73eff5a9d`
- コミット URL: https://github.com/Jakeschincariol/founder-skill/commit/fd9385b0cfe1b96bebce3898fbd506d73eff5a9d
- 確認日: 2026-10-25

原作の README、LICENSE、11 本の SKILL.md、founder-board/lenses.md を確認したうえで構成を翻案しました。原作の Python プログラムは同梱していません。原作の著作権通知と MIT 許諾文・免責文を LICENSE に保持しています。本体 TXT にも同じ通知を含めています。

## 11 分野の対応

| 原作の実ファイル | 本版 | 主な扱い |
| --- | --- | --- |
| skills/founder-board/SKILL.md | アイデア | 価値・差別化・体験の 3 観点。同一会話で検討 |
| skills/founder-competitors/SKILL.md | 競合 | 直接/間接/代替、価格、公開資料、根拠 URL |
| skills/founder-consumer/SKILL.md | 仮想顧客 | 最初 5 視点。独立エージェントや実顧客調査ではない |
| skills/founder-pricing/SKILL.md | 価格 | 原価・競合・実測データからテスト候補を整理 |
| skills/founder-offer/SKILL.md | オファー | 反論に対応する提供物と追加原価・履行可能性 |
| skills/founder-cfo/SKILL.md | 採算 | 式と単位を明示した試算、欠損・能力・資金の点検 |
| skills/founder-marketing/SKILL.md | 集客 | 2〜3 チャネル、30 日、計測と許容 CAC |
| skills/founder-brand/SKILL.md | ブランド | 名前、約束、表現、権利・利用可否の未確認を明示 |
| skills/founder-ops/SKILL.md | 運営 | 担当・作業・能力・原価・許認可の確認 |
| skills/founder-launch/SKILL.md | 実地検証 | 小さな現実のテスト、事前基準、開始後レビュー |
| skills/founder-plan/SKILL.md | 事業計画 | 採算モデルと需要の証拠を別々に判定 |

実ファイルの固定版は、次の URL の下に上記のパスを続けたものです。
https://github.com/Jakeschincariol/founder-skill/blob/fd9385b0cfe1b96bebce3898fbd506d73eff5a9d/

## 公開フレームワークへの言及

原作の founder-board/lenses.md は、Alex Hormozi『$100M Offers』、Peter Thiel / Blake Masters『Zero to One』、Walter Isaacson『Steve Jobs』を出典に、独自の言葉で観点を要約しています。本版も経営者本人の発言や演技ではなく、観点として扱います。これらの書籍本文・引用は同梱しません。

## 本版で変更した点

- 英語の Claude 向けスキルを、通常の ChatGPT 会話に貼り付ける日本語の段階式プロンプトへ再構成。
- インストール、ファイルシステム、Claude の Agent ツール、Python 実行への依存を除去。
- 初回を少数の視点で行い、利用者が求めたときだけ増やす。
- 同じ AI による架空反応は、独立した標本でも需要予測の上限でもないと明示。
- 架空回答による価格帯や購入率を、実際の需要・売上・LTV・CAC の根拠にしない。
- 原作の Van Westendorp ツール、シード付き人物生成、集計、compile.py の自動判定は移植していない。
- 原作の疑似購入率の閾値を利用した判定の代わりに、「仮定上の採算」と「需要の実測」を分離。
- 未調査・未計算・未実施を残し、出典捏造、外部資料からの命令、未承認の公開や購入を避ける指示を追加。
- 月単位の計算式、初期支出と営業利益の区別、手計算時の要検算表示を追加。
- 入力テンプレート、架空の数値例、確認リストを追加。

## 非公式性

本版は、原作者、OpenAI、Anthropic、または言及された著者による公式製品・監修・推薦を示しません。各サービスの名称は対応する利用環境の説明に使っています。

新たな実顧客データ、非公開の企業情報、認証情報は含みません。架空例はすべて説明・検算のためのものです。
