# KATAPATA Stripe API v42

Vercelで `No exports found in module` が出た場合の修正版です。
CommonJS の `module.exports` ではなく、ES Module の `export default` 形式に変更しています。

## 置き換えるファイル

- `api/create-checkout-session.js`
- `api/verify-checkout-session.js`
- `package.json`

## 配置

GitHubリポジトリのルートに置きます。

```text
katapata-site-test/
├─ api/
│  ├─ create-checkout-session.js
│  └─ verify-checkout-session.js
├─ package.json
├─ index.html
└─ tools/
```

## 環境変数

Vercelの Production に以下を設定します。

- `STRIPE_SECRET_KEY`
- `KATAPATA_PURCHASE_TOKEN_SECRET`
- `STRIPE_PRICE_ID` は任意

置き換え後、Vercelで Redeploy してください。
