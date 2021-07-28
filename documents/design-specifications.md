# FFXIV Crafter Generator 設計書

## 全体構成

* View
  * Controller-Model
    * DB
    * API

### View

UI/UXの提供を行う。

#### 使用言語

未定

#### 使用フレームワーク

未定

#### 構成

### Controller-Model

Viewに対するバックエンド部分の処理を行う。

#### 使用言語

Ruby

#### 使用フレームワーク

Ruby on Rails

#### 構成

### DB

バックエンド処理に用いるデータの管理を行う。

#### 使用DBドライバ

MySQL

#### テーブルリスト

### API

アプリケーションのコアとなるスキル回し生成機能を単一のAPIとして実装する。

#### 使用言語

Go

#### 使用フレームワーク

Echo

#### 構成
