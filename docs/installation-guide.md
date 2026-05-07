# インストールガイド

## Closed Alpha Package

1. GitHub Release `v0.1.0-alpha.1` から assets を取得する。
2. `dist/image-asset-alt-qa-cart-docs.zip` を展開して README と manual-test を確認する。
3. repo を clone する場合:

```powershell
git clone https://github.com/Sunmax0731/image-asset-alt-qa-cart.git
cd image-asset-alt-qa-cart
npm test
```

## Host Setup

1. 作業ディレクトリ `D:\AI\ChromeExtension\image-asset-alt-qa-cart` で `npm test` を実行します。
2. Chrome の `chrome://extensions` を開き、Developer mode を有効にします。
3. `extension/` を Load unpacked で読み込みます。
4. 任意の公開ページまたはYouTubeページを開き、ポップアップと content script の表示を確認します。

