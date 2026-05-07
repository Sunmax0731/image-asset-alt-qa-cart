# 画像・素材・alt検品カート

image-asset-alt-qa-cart は Web制作担当者、アクセシビリティレビュー担当者、素材管理者 向けの closed alpha プロダクトです。ページ上の画像、alt、用途、権利情報を一時カートへ入れ、公開前の不足を検品する。

## Source

- PICKUP Rank: 42
- Domain / Idea No: ChromeExtension / 7
- Repository: image-asset-alt-qa-cart
- 主な公開先: Chrome Web Store
- created_idea: `D:/AI/ChromeExtension/created_idea_007_image-asset-alt-qa-cart`
- 同梱ZIP: `D:/AI/ChromeExtension/created_idea_007_image-asset-alt-qa-cart/idea_007_image-asset-alt-qa-cart.zip`
- 開始時 README: 存在しない


## Alpha Scope

- 代表シナリオ4件の自動検証
- 必須項目不足、警告、混在バッチの分類
- extension/ のホスト連携シェル
- QCDS、security/privacy、traceability、release checklist、manual test docs
- docs ZIP: `dist/image-asset-alt-qa-cart-docs.zip`

## Commands

```powershell
npm test
node src/cli/index.js samples/representative-suite.json
npm run build:docs
```

手動テストは Codex 側では未実施です。手順は `docs/manual-test.md` と `docs/strict-manual-test-addendum.md` にあります。

