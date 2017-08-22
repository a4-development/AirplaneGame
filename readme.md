# UnityProject
## 作成物
-挙動を調整したaircraftオブジェクト
-ゲームモード選択画面+管理スクリプト
-オプション画面+管理スクリプト
-ゲームステージ管理スクリプト
-コース上のオブジェクト(得点オブジェクトやコースオブジェクト)
-ゴールオブジェクト
## 今後の改善案
-機体スクリプトを「進んで良いかどうか」のbool値で判断するようにする。
-ステージの壁はオブジェクトにした方がいいか。それともbool値で判断するか。左右旋回は自由。bool値は各軸2つ、計6つの上限値のfloat値内に収まっているかどうかで判断する
-簡単なコースオブジェクトを作って、機体との距離を計るスクリプトを作る。
http://blog.livedoor.jp/bribser_dev/archives/4230746.html
-ゴールオブジェクトを作る。
-ゴールなどへの接触を判定する統合的なステージスクリプトを書く。
## Tips
-masterブランチは使わない。
-キャラクターのアクションを実装するなど部分部分の作業をする人が専用のfeatureブランチを切って開発していく。
-少し進めたら「ここまで実装できた」と目印を作り、テストを終えてdevelopブランチに結合する。
-こうすると問題発生時の被害を抑えられ