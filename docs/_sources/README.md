# Intro to SAS Notes

University of Florida College of Public Health and Health Professionsが公開しているSASのテキストを日本語にして公開予定です。  
https://users.phhp.ufl.edu/rlp176/Courses/PHC6089/SAS_notes/intro.html

データについてはライセンスが明確ではなかったので、公開元からの取得をお願いします。  
https://users.phhp.ufl.edu/rlp176/Courses/PHC6089/data/

## コードの変更点

以下動作には影響しませんが、実際によく書かれている・便利なコーディングに合わせ以下のように統一しました。
- インデント幅を2に統一
- ライブラリ・変数名以外は小文字を使用
- グローバルステートメントをプロシージャ内から前に移動
- 配列の()を他の種類に変更
- マクロ変数の使用時にピリオドを記載、call symputxを使用