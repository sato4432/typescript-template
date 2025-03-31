# TypeScript Reactテンプレート

このリポジトリは、TypeScriptとReactを使用したプロジェクトのテンプレートです。ESLintとPrettierによるコード品質の管理と一貫したコードスタイルを提供します。

## 機能

- **TypeScript** - 静的型付けによる安全なコード開発
- **React** - UIコンポーネントの構築
- **ESLint** - コード品質の管理と問題の検出
- **Prettier** - 一貫したコードフォーマット

## セットアップ

```bash
# リポジトリをクローン
git clone https://github.com/yourusername/typescript-template.git
cd typescript-template

# 依存関係のインストール
npm install
```

## 使用方法

```bash
# 開発サーバーの起動
npm start

# プロダクションビルド
npm run build

# テストの実行
npm test

# リントチェック
npm run lint

# リント問題の自動修正
npm run lint:fix

# コードフォーマット
npm run format

# フォーマットチェック
npm run format:check
```

## ESLint設定

厳格なコード品質のルールが適用されています：

- TypeScriptの厳格な型チェック
- 未使用変数の検出
- any型の使用禁止
- 明示的な戻り値の型定義の強制
- 非nullアサーションの禁止
- console.logの使用警告（warnとerrorは許可）
- 等価演算子（===）の強制
- 波括弧の強制

## Prettier設定

コードの一貫したフォーマットのための設定：

- セミコロン: 必須
- シングルクォート: 使用
- タブ幅: 2スペース
- 最大行長: 100文字
- 末尾カンマ: すべての場所で必須
- 括弧のスペース: 使用
- 括弧の配置: 新しい行
- アロー関数の括弧: 常に使用
- 改行コード: LF

## ライセンス

MITライセンスの下で公開されています。詳細はLICENSEファイルを参照してください。

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
