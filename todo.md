## やること
- ゼロから作るDeeplearningの1と2から抜粋して、以下の実装をして内部理解
  - Dence
  - CNN, Pooling
  - RNN
  - LSTM
  - Attention
  - word2vec
  - seq2seq
- 精度をあげる時の手法についてまとめる、サンプルコードを書く（毎回1テーマくらい）

-----

## 疑問解明会
- ch2　dataaugumentationするとtestデータでaccuracyあがらなくなる
- ch2 fine-tuningの重み
- ch2 勾配消失が起きているかの確認
- ch2 フィルタ数の選び方

## 第一回
- Denceの実装（もしできれば。ゼロから作るを参考に実装）
- fine-tuning（重みのみver)
  - ch02の課題でチャレンジ。VGG16から重みを転移して使う
- 偏りのあるデータの前処理
  - ch03の課題でチャレンジ。偏りがあるデータに対する前処理をしてみる

## 第二回
- CNN, Poolingの実装
- fine-tuning（全部使うver）
- 時系列データの前処理

-----

## 第二回
- word2vec＋自然言語処理の基礎
- TTA、KFold
- 実装面（LearningRateScheduler、EarlyStoppingなど実装のtips）
- optimizer探索
- ハイパーパラメータ探索

## 第三回
- アンサンブル
- RNN実装

## 第四回
- LSTM実装
- Attention実装
- seq2seq実装
