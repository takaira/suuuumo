# SUUMO情報取得と地図APIを用いた物件検索システム

## プログラムなし

スクレイピングという処理を利用する都合上プログラムについては共有できないので、PowerPointファイルのみを共有してます。

## 概要

このプロジェクトは、SUUMOから物件情報を取得し、地図API (Yolp) を使用して直線距離から物件を検索可能にするWebアプリケーションです。満員電車を避け、徒歩で通勤できる物件を見つけることを目的としています。

- **背景**: 満員電車に乗りたくなく、徒歩で通勤したい
- **目的**: 徒歩圏内の物件を検索し、住む部屋を見つけること

## 機能

### ユーザー側

- **アカウント登録**: ID、パスワード、職場住所の登録
- **職場住所の変更**: 登録後に職場住所を変更可能
- **検索機能**: 職場から指定した半径内の物件を検索
- **一覧表示機能**: 検索結果を一覧で表示

### 管理者側

- **SUUMOから情報取得**: スクレイピングでSUUMOの物件情報を取得
- **住所から座標の算出**: APIを用いて住所から座標を取得
- **座標間の距離算出**: 座標間の直線距離を算出
- **データベース登録**: 取得した物件情報をデータベースに登録

## 使い方

1. ブラウザでアプリケーションにアクセスします。
2. ユーザーはアカウントを登録し、職場住所を設定します。
3. 職場住所の変更や物件の検索が可能です。
4. 管理者はSUUMOから物件情報を取得し、データベースに登録します。