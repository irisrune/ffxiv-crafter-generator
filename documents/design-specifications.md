# FFXIV Crafter Generator 設計書

## 全体構成

* View
  * API
    * DB
### View

UI/UXの提供を行う。

#### 使用言語

typescript

#### 使用フレームワーク

未定

#### 構成

### API

Viewに対するバックエンド部分の処理を行う。
スキル回し生成機能を含む。

#### 使用言語

Rust

#### 使用フレームワーク

未定

#### 構成

### DB

バックエンド処理に用いるデータの管理を行う。

#### 使用DBドライバ

MySQL or NOSQL

#### テーブルリスト

1. recipes 製作レシピ
2. foods 食事
3. medicines 薬
