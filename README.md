# 開発工数見積もりツール

社内SE向けの開発プロジェクト工数見積もりツールとガイドのコレクションです。

## 概要

このプロジェクトは、開発プロジェクトの工数を正確に見積もるためのツールと、見積もりルールを理解するための解説ガイドを提供しています。効率的なプロジェクト管理と適切なリソース配分を実現するために設計されています。

## ツール一覧

### 1. 社内SE開発工数見積ツール
- **ファイル**: `Estimated man-hours.html`
- **概要**: 開発プロジェクトの工数を効率的に見積もるための実用的な計算ツール
- **主な機能**:
  - 開発規模に基づく基本工数の自動計算
  - 技術難易度・複雑度の考慮
  - リスク要因による調整係数の適用
  - フェーズ別の工数内訳表示
  - 見積もり結果のエクスポート機能

### 2. 開発工数見積ルール解説ガイド
- **ファイル**: `estimate-rules-guide.html`
- **概要**: 工数見積もりのルールと考え方をビジュアルで分かりやすく解説
- **主な機能**:
  - 見積もりの基本原則と考え方の解説
  - 工数算出の具体的な手順
  - よくある見積もりの落とし穴と対策
  - ビジュアルでわかりやすい解説
  - 実践的なケーススタディ

## 使用方法

1. `index.html`をWebブラウザで開きます
2. ポータルページから使用したいツールを選択します
3. 各ツールの指示に従って操作してください

### 開発工数見積ツールの使い方

1. プロジェクトの基本情報を入力
2. 開発規模（画面数、機能数など）を指定
3. 技術的な難易度を選択
4. リスク要因をチェック
5. 「計算する」ボタンをクリックして結果を確認

### 解説ガイドの使い方

1. 目次から学習したいセクションを選択
2. ビジュアル解説を確認しながら理解を深める
3. 実践的なケーススタディで知識を定着

## 技術仕様

### 対応ブラウザ
- Chrome (推奨)
- Firefox
- Safari
- Edge

### レスポンシブ対応
- デスクトップ: 1200px以上
- タブレット: 768px - 1199px
- モバイル: 767px以下

### 使用技術
- HTML5
- CSS3 (CSS Variables, Flexbox, Grid)
- JavaScript (ES6+)
- ローカルストレージ（設定保存用）

## 主な機能詳細

### 工数計算機能
- **基本工数計算**: 画面数、API数、バッチ処理数から基本工数を算出
- **難易度調整**: 技術的な複雑さに応じて係数を適用
- **リスク調整**: プロジェクトリスクを考慮した補正
- **フェーズ別配分**: 設計、開発、テストなど各フェーズへの工数配分

### 見積もりルール
- **標準工数**: 各開発要素の標準的な工数定義
- **調整係数**: 状況に応じた工数調整のルール
- **品質保証**: テスト工数の適切な配分基準
- **バッファ**: 不確実性に対する適切なバッファの考え方

## ファイル構成

```
開発工数見積もり/
├── index.html                    # ポータルページ
├── Estimated man-hours.html      # 開発工数見積ツール
├── estimate-rules-guide.html     # 見積ルール解説ガイド
└── README.md                     # このファイル
```

## カスタマイズ

### カラーテーマ
CSS変数を使用してカラーテーマをカスタマイズできます：

```css
:root {
    --primary-color: #005BAB;      /* メインカラー */
    --secondary-color: #FF961C;    /* アクセントカラー */
    --light-blue: #E0EEF9;        /* 背景色 */
    --text-dark: #333333;         /* テキストカラー */
}
```

### 工数係数の調整
各組織の実情に合わせて、以下の係数を調整可能：
- 基本工数単価
- 技術難易度係数
- リスク調整係数
- フェーズ別配分比率

## ベストプラクティス

### 見積もり精度向上のポイント
1. **詳細な要件定義**: 曖昧な要件を明確化してから見積もる
2. **過去実績の活用**: 類似プロジェクトの実績を参考にする
3. **段階的な精緻化**: プロジェクト進行に応じて見積もりを更新
4. **バッファの適切な設定**: リスクに応じた適切なバッファを確保

### よくある失敗と対策
- **楽観的な見積もり**: 実績ベースで現実的な数値を使用
- **スコープクリープ**: 要件変更管理プロセスの確立
- **技術的リスクの軽視**: 新技術導入時は十分なバッファを確保
- **コミュニケーションコスト**: チーム規模に応じたオーバーヘッドを考慮

## トラブルシューティング

### よくある質問

**Q: 計算結果が表示されない**
A: JavaScriptが有効になっているか確認してください

**Q: エクスポート機能が動作しない**
A: ブラウザのポップアップブロッカーを確認してください

**Q: モバイルで表示が崩れる**
A: 最新のブラウザバージョンを使用してください

## 更新履歴

- 2024年 - 初版リリース
- 2024年 - レスポンシブデザイン対応
- 2024年 - ポータルページ追加
- 2024年 - ビジュアル解説機能強化

## ライセンス

このツールは社内利用を目的として開発されています。

## サポート

問題や改善提案がある場合は、開発チームまでご連絡ください。

---

© 2024 開発工数見積もりツール. All rights reserved.
