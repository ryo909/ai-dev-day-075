# Day075 Story — Event Role Badge Mixer

## Why
毎日使う小さな課題を、1ページで即解決できる形にしたかったため。

## Requirements
- Webブラウザだけで完結すること
- 1画面で主要操作が終わること
- GitHub Pagesで公開できること

## Design highlights
- Day075専用にテーマをseed固定して再生成時の見た目を安定化
- utility用途に寄せた単機能UIで迷いを減らす
- 出力をそのまま再利用できるテキスト構造
- Family: role_badge_fun_play
- Mechanic: fun_card_mix
- Input/Output: people_chips -> certificate_card
- Audience Promise: 堅くならずに役割をその場で渡せる。
- Publish Hook: 人と係を入れると、負担が偏りすぎないバッジが遊び感のあるカードで配れる。
- Complexity Tier: small
- Selected components: none
- Complexity hint: Implement the locked brief with one clear hero interaction and keep the main screenshot readable.

## Trade-offs / Known issues
- ローカル保存機能は未実装
- 複雑な入力バリデーションは最小限

## Next ideas
- 履歴保存
- プリセット追加
- エクスポート形式拡張

## Social copy
Day075｜係バッジ混ぜ
集まりの軽い係をバッジで配るツールです。
