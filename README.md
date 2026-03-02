# あつ森株価予想

あつまれ どうぶつの森（ACNH）のカブ価推移予測ツールです。
https://hayaokuri.github.io/Animal-Crossing-Stock-price-prediction/

## 機能
- **推移予測**: 入力されたカブ価から、今後の価格推移パターンと各時間帯の最大・最小値を算出します。
- **データ保存**: 入力値はブラウザ（`localStorage`）に自動保存され、日曜日に前週パターンを自動で引き継ぎます。
- **URL共有**: 現在の入力状態を含んだパラメータ付きURLを発行し、予測結果を共有できます。

## 使い方
1. 先週の変動パターンと初回購入フラグを選択します。
2. 日曜日の買値と、月曜日以降の売値を入力します。
3. 自動で計算結果と推移グラフが更新されます。

## デプロイ環境
本ツールは静的ファイル（HTML/JS）のみで構成されています。
GitHub Pages等の静的ホスティング環境のルートディレクトリに配置するだけで動作します。

## クレジット
本ツールは以下の解析および実装に基づいています。
- アルゴリズム解析: [Treeki/TurnipPrices.cpp](https://gist.github.com/Treeki/85be14d297c80c8b3c0a76375743325b)
- 予測ロジック実装: [mikebryant/ac-nh-turnip-prices](https://github.com/mikebryant/ac-nh-turnip-prices)
