# EnablerDAO Agents

100匹の自律AIエージェント犬のレジストリ。

## 構成

| ホスト | 犬数 | 備考 |
|-------|:----:|------|
| Fly.io (nrt) | 11 | コア犬 + プロダクト犬 |
| Hetzner | 89 | Tech / Business / Creative / Science / Lifestyle / DAO / Utility |

## ファイル

- `agents.json` — 全100匹の名前・カテゴリ・ホスト・専門分野

## カテゴリ

| カテゴリ | 犬数 | 例 |
|---------|:----:|-----|
| core | 6 | Bossdog, Motherdog, Guarddog |
| product | 15 | Chatwebdog, Stayflowdog, Solunadog |
| tech | 20 | Aidog, Rustdog, Wasmdog, Blockchaindog |
| business | 10 | Marketingdog, Financedog, Strategydog |
| creative | 8 | Musicdog, Gamedog, Artdog |
| science | 8 | Mathdog, Spacedog, Robotdog |
| lifestyle | 7 | Fooddog, Traveldog, Educationdog |
| dao | 7 | Tokendog, Daodog, Defidog, Nftdog |
| utility | 19 | Searchdog, Paymentdog, Analyticsdog |

## アクセス制御

全操作に **ENABLER Member NFT** (Solana) の保有が必要。

| 項目 | 値 |
|------|-----|
| NFT Mint | `A9rhRaxkD7gBxsmxgBhxTbzPZQD43sC5ryXcX8XDj1Ft` |
| 総供給量 | 4 (ミント権限は保持) |
| Decimals | 0 |
| チェック方法 | `GET /wallet/{address}/nft` |
| ネットワーク | Solana Mainnet |

## 関連リポジトリ

- [yukihamada/rustydog](https://github.com/yukihamada/rustydog) — Dog Pack 本体 (Rust + WASM)
- [enablerdao/enablerdao.com](https://github.com/enablerdao/enablerdao.com) — EnablerDAO サイト

## ライセンス

MIT
