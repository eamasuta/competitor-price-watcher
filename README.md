## Implementation Tasks (MVP)

> このセクションは **GitHub Issue と1:1対応**しています  
> 各タスクは 1 Issue = 1〜3時間 を想定しています  
> 実装は Issue を起点に行い、READMEは進捗の俯瞰に使用します

---

### Epic 0: プロジェクト土台

- [ ] **Issue #0-1** リポジトリ初期化（Next.js + App Router）
- [ ] **Issue #0-2** Postgres + Prisma セットアップ（初期マイグレーション）

---

### Epic 1: 認証（メール＋パスワード）

- [ ] **Issue #1-1** Userモデル実装（Prisma）
- [ ] **Issue #1-2** パスワードハッシュ化ユーティリティ
- [ ] **Issue #1-3** サインアップAPI
- [ ] **Issue #1-4** ログインAPI＋セッション
- [ ] **Issue #1-5** 認証ガード（未ログインリダイレクト）
- [ ] **Issue #1-6** Login画面（UI + API）

---

### Epic 2: Competitor CRUD

- [ ] **Issue #2-1** Competitorモデル実装（Prisma）
- [ ] **Issue #2-2** Competitor作成API
- [ ] **Issue #2-3** Competitor一覧API
- [ ] **Issue #2-4** Competitor更新API
- [ ] **Issue #2-5** Competitor削除API

---

### Epic 3: ダッシュボードUI

- [ ] **Issue #3-1** Dashboard画面（一覧表示）
- [ ] **Issue #3-2** 競合追加UI
- [ ] **Issue #3-3** 一覧から削除UI

---

### Epic 4: 詳細画面

- [ ] **Issue #4-1** Competitor詳細API
- [ ] **Issue #4-2** Competitor Detail画面

---

### Epic 5: 取得・差分判定（コア）

- [ ] **Issue #5-1** HTML→テキスト正規化
- [ ] **Issue #5-2** ハッシュ生成（SHA-256）
- [ ] **Issue #5-3** ページ取得処理
- [ ] **Issue #5-4** 差分判定＆DB更新サービス

---

### Epic 6: 定期実行

- [ ] **Issue #6-1** バッチ実行API（手動トリガー）
- [ ] **Issue #6-2** 定期実行設定（README記載）

---

### Epic 7: エラー表示とUX

- [ ] **Issue #7-1** Dashboardで取得エラー表示
- [ ] **Issue #7-2** APIエラーレスポンス統一

---

### Epic 8: ダミーデータ

- [ ] **Issue #8-1** Seedスクリプト作成

## Task Management Rules

- 実装は必ず GitHub Issue を起点に行う
- README のチェックボックスは進捗の可視化用
- 完了条件は Issue の Acceptance Criteria を優先する
- README は仕様書ではなく「作業俯瞰用ドキュメント」とする

