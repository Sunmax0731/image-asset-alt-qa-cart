# 要件定義

## 目的

画像・素材・alt検品カート は、Web制作担当者、アクセシビリティレビュー担当者、素材管理者 が ページ上の画像、alt、用途、権利情報を一時カートへ入れ、公開前の不足を検品する。

## Source

- PICKUP Rank: 42
- Domain / Idea No: ChromeExtension / 7
- Repository: image-asset-alt-qa-cart
- created_idea: `D:/AI/ChromeExtension/created_idea_007_image-asset-alt-qa-cart`
- ZIP: `D:/AI/ChromeExtension/created_idea_007_image-asset-alt-qa-cart/idea_007_image-asset-alt-qa-cart.zip`
- README確認: 開始時点では正式 repo が存在しないため、README.md は存在しない。

## Functional Requirements

- R1: assetName、altText、usageContext、license を必須項目として検査する。
- R2: 必須項目不足は fail として分類する。
- R3: `decorativeAmbiguous` が true の場合は warning として分類し、手動確認理由を返す。
- R4: 複数アイテムの mixed-batch を pass / warning / fail に集計する。
- R5: 結果を CLI と docs/release evidence で再利用できる形にする。

## Non Functional Requirements

- UTF-8 で Markdown / JSON / JS / HTML / Python を保存する。
- 外部通信を既定で行わず、サンプルとローカル入力だけで検証できる。
- 手動テスト未実施であることを release 前 docs に明記する。

