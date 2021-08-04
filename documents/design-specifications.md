# FFXIV Crafter Generator 設計書

## 全体構成

* View
  * Controller-Model-DB
  * API

### View

UI/UXの提供を行う。

#### 使用言語

未定（gatsbyjsなど候補）

#### 使用フレームワーク

未定

#### 構成

### Controller-Model

Viewに対するバックエンド部分の処理を行う。

#### 使用言語

Ruby or firebase

#### 使用フレームワーク

"Ruby on Rails" or firebase

#### 構成

### DB

バックエンド処理に用いるデータの管理を行う。

#### 使用DBドライバ

MySQL or NOSQL

#### テーブルリスト

1. recipes 製作レシピ
2. foods 食事
3. medicines 薬

### API

アプリケーションのコアとなるスキル回し生成機能を単一のAPIとして実装する。

#### 使用言語

Go

#### 使用フレームワーク

Echo

#### 構成

* main API本体
  * generator コア部分
    * condition 工数・品質・状態・ターン数をまとめた物
      * buffs バフ
    * skills スキル
    * calculator 各種計算機
