概要
-------------------------

以下の要素を含む簡単な Spring Boot アプリケーションです。

* Spring Security
  - 認証（ログイン・ログアウト、DBユーザ及びインメモリ認証）
  - 認可（権限によるメニュー制御）
  - Remember-Me（ブラウザを閉じてもログイン状態を保持）
* Thymeleaf Layout Dialect で共通レイアウト
* 共通エラーページ（error.html）
* DataTables でテーブル実装
* オフキャンバスメニューのレスポンシブ対応

画面
-------------------------

### H2 コンソール
<img width="1000" src="https://user-images.githubusercontent.com/59589496/132644259-6f5cda3a-7848-4214-9915-1032ae22d718.png">  

### ログインページ
<img width="600" src="https://user-images.githubusercontent.com/59589496/132644649-951e8995-3f77-4e3b-8916-e533e6a47ed3.png">  

### ユーザ登録ページ
<img width="600" src="https://user-images.githubusercontent.com/59589496/132644778-7a148aae-02b9-484b-98a3-a20271d1674d.png">  

### ログイン情報ページ
ログインユーザを表示するページ  
<img width="1000" src="https://user-images.githubusercontent.com/59589496/132645013-de3b6b4c-625c-40bf-8622-4e2ba2a2dd0c.png">  

### ユーザ一覧ページ
管理者（ADMIN）権限のみ表示可（認可制御）  
<img width="1000" src="https://user-images.githubusercontent.com/59589496/132645340-deca83da-147c-4ff4-b8b7-9ad4bf25b523.png">  

### 共通エラーページ
<img width="1000" src="https://user-images.githubusercontent.com/59589496/132645533-cbca01e5-6257-46f1-b75a-cba2d53fd9ec.png">  

### ログアウト
<img width="600" src="https://user-images.githubusercontent.com/59589496/132645684-2879f6da-a727-4ebe-be38-951c9a6c46b0.png">  

### ログイン認証エラー
<img width="600" src="https://user-images.githubusercontent.com/59589496/132647273-636e0ab8-c850-4dac-ae33-c4b7f8f662fe.png">  

フォルダ構成
-------------------------

<img width="320" src="https://user-images.githubusercontent.com/59589496/132646644-abbe81a7-39cd-4ee8-adcd-bfe1ba9dd1a8.png">  

依存関係
-------------------------

* Spring Boot DevTools
* Thymeleaf
* Thymeleaf Layout Dialect
* Spring Web
* Validation
* Spring Data JPA
* H2 Database
* Spring Security
* Lombok
* WebJars
  - Bootstrap
  - Bootstrap Icons
  - DataTables
  - DataTables Plugins
  - DataTables Buttons
