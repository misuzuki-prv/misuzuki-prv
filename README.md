### Hi, I'm misuzuki-prv

オンプレミス／オフライン環境での LLM 基盤構築と、3D GIS Web アプリケーション開発を主に担当しているエンジニアです。
*On-prem LLM platforms, code-aware RAG, and 3D GIS on the web.*

## 主な領域 / Focus

- **オンプレ LLM 推論基盤** — vLLM / Ray による推論サーバ構築、LiteLLM でのモデルルーティング、Open WebUI の整備、Roo Code / Zoo Code などのコーディングエージェントをローカル LLM で動かす環境づくり
- **コードベース・設計書の RAG / GraphRAG** — ソースコードや設計ドキュメントを Neo4j（グラフ）と Qdrant / Milvus（ベクトル）に取り込み、検索・質問応答に使える形にするパイプライン
- **3D GIS Web アプリ** — CesiumJS / WebGL / WebGPU による大規模データの 3D 可視化。フロントエンド（Angular / React）からバックエンド（Node.js / Python）まで一貫して担当
- **生成 AI による開発プロセス改善** — 既存の開発プロセス・成果物を活かしたまま、AI が扱いやすい中間形式を挟んで工程を効率化する取り組み
- **インフラ** — ネットワーク・Linux・AWS の構築経験がベース

## 個人開発 / Side Projects

### POSONE（2026年8月リリース）
トレーディングカード販売者向けの Web SaaS。在庫管理、損益の記録・集計、鑑定（PSA）提出の管理をまとめて扱えます。
- 設計から実装・運用まで一人で担当し、コーディングエージェント（Claude Code）を全面的に活用して開発
- Vercel + Supabase、Stripe Billing によるサブスクリプション課金
- MCP コネクタを提供し、ユーザーが自分のデータを AI アシスタントから問い合わせられるようにした
- 構造化データの整備など、生成 AI 検索からの見つけやすさ（GEO）も意識して実装
- ※ ソースコードは非公開です

## OSS

- [graphify](https://github.com/Graphify-Labs/graphify)（コードのナレッジグラフ化ツール）に JSP（JavaServer Pages）用の extractor を追加するコントリビューション（[PR](https://github.com/Graphify-Labs/graphify/pull/4458)）

## 関心領域 / Interests

- ローカル LLM と推論の高速化（speculative decoding など）
- 大規模可視化のためのデータ指向設計（ECS）
- AI ネイティブな開発プロセス

## 資格 / Certifications

| 資格 | 取得 |
| --- | --- |
| AWS Certified SAP on AWS – Specialty | 2024/04 |
| 応用情報技術者 | 2023/11 |
| ORACLE MASTER Bronze DBA | 2023/03 |
| AWS Certified Solutions Architect – Associate | 2022/12 |
| LPIC-3 305 | 2022/08 |
| CCNA | 2022/06 |

## 技術スタック / Tech Stack

| 分野 | 技術 |
| --- | --- |
| LLM / AI | vLLM, Ray, LiteLLM, Open WebUI, Roo Code / Zoo Code, Claude Code, MCP |
| RAG / データ | Neo4j, Qdrant, Milvus |
| GIS / 可視化 | CesiumJS, WebGL, WebGPU, Re:Earth, PLATEAU, TerriaJS, Google Earth Engine, GeoServer, GDAL, QGIS |
| フロントエンド | JavaScript, Angular, React |
| バックエンド | Node.js, Python (Flask, Tornado) |
| Web / SaaS | Vercel, Supabase, Stripe |
| インフラ / CI | AWS, Linux, ネットワーク, GitHub Actions |
