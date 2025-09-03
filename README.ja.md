# 12週間フロントエンド学習ロードマップ（ポートフォリオ付き）

## 📅 概要
- **期間**: 12週間（平日: 1時間/日、土日: 最大4時間/日 = 約13時間/週）
- **目標**: JS/TS/Reactの基礎を固め、Next.js/Redux/Testingなどのモダンフロント技術を習得し、最終的に「国際対応ダッシュボード」MVPを完成させる。

---

## ✅ 進捗トラッカー

### Phase 1: 基礎固め（Week 1–3）
- [ ] **Week 1–2: JavaScript基礎再構築**
  - 学習: this、クロージャ、非同期処理、配列操作
  - 演習: map/filter/reduce、Promise vs async/await
  - 成果物: [JS基礎リポジトリ](./week1-2-js-fundamentals)
- [ ] **Week 3: TypeScript基礎**
  - 学習: 型注釈, interface, generics, union/narrowing
  - 演習: TodoアプリをTS化（any禁止）
  - 成果物: **coming soon**

### Phase 2: React実践（Week 4–6）
- [ ] **Week 4: React復習**
  - 学習: useState, useEffect, props, コンポーネント分割
  - 演習: 掲示板アプリ（投稿＋一覧表示）
  - 成果物: React掲示板
- [ ] **Week 5: Advanced React**
  - 学習: Context, useMemo, useCallback, ErrorBoundary
  - 演習: Dashboard風UIをContext＋パフォーマンス最適化
  - 成果物: Advanced Dashboard
- [ ] **Week 6: React Testing**
  - 学習: Jest + React Testing Library + MSW
  - 演習: Week4掲示板にテスト追加（ユニット＋統合）
  - 成果物: テスト済み掲示板

### Phase 3: Next.jsと状態管理（Week 7–9）
- [ ] **Week 7: Next.js基礎**
  - 学習: App Router, SSR/SSG/ISR, API Routes
  - 演習: ブログ風記事一覧＋詳細（ISR対応）
  - 成果物: Next.jsブログ
- [ ] **Week 8: Redux Toolkit**
  - 学習: Slice, asyncThunk, RTK Query
  - 演習: ECサイト風カート機能
  - 成果物: RTKカート
- [ ] **Week 9: Build Tools & CSS-in-JS**
  - 学習: Vite/webpack比較、Styled-components/Emotion
  - 演習: テーマ切替（ライト/ダーク）
  - 成果物: テーマ切替デモ

### Phase 4: MVP構築（Week 10–12）
- [ ] **Week 10: MVP設計 & 認証**
  - 設計: 国際対応ダッシュボード（ページ構成、状態管理方針、i18n設計）
  - 実装: 認証（Firebase Auth or Cognito）＋ルーティング
  - 成果物: MVPスケルトン
- [ ] **Week 11: CRUD & 多言語対応**
  - 実装: 投稿のCRUD（記事やコメント）
  - 実装: i18n（英語/日本語切替）
  - 成果物: 多言語対応ダッシュボード
- [ ] **Week 12: 仕上げ**
  - 実装: ダーク/ライトテーマ統合、API連携、テスト追加
  - CI: GitHub Actionsで自動テスト
  - 成果物: 完成版MVP（国際対応ダッシュボード）

---

## 🚀 最終MVP機能
- 認証（Firebase Auth or Cognito）  
- 投稿のCRUD（記事やコメント）  
- 多言語対応（日本語/英語切替）  
- ダーク/ライトテーマ  
- ユニット＋統合テスト  
- CI/CD（GitHub Actions）  

デモ: **coming soon**
