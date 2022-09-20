　ご高覧いただき誠にありがとうございます。中山裕司と申します。
　 　
　 　
　　　　 　
成果物として「登録」「ログイン」の手順書である「勤怠情報手順書」ZIPファイルがございます。
　 
　以下は私の4月からの取り組み経緯となるので、上記の「勤怠管理手順書」の中にある
「社員登録手順書」と「ログインと勤怠情報登録手順書」だけでも
拝見していただけると幸いでございます。
 　　
  　　
 　　
　現在JAVAの研修後、自習時間を使い様々なアプリケーションの本を写経し、学んだことを使いながら勤怠管理システムを０から作成しております。
また、Javaからデータベースの基礎的な4大命令操作ができます。
まだまだ未実装（張りぼて）の箇所もありますが、これからどんどんブラッシュアップしていこうと考えております。
  　
  　
　主な役割として
・「register」ファイルでは管理者としてDBに社員登録を行ったり、検索ができるようにします。
・「login」ファイルではDBに登録された社員IDでログインし、勤怠管理システムに勤務表を作成していきます。
 　
 　
 　
以上が2022年8月26日現在での私の勤怠システム管理の状態です。
　 　
  　　
 　　
 　　
   　
今後の目標：
　「学ぶ」とは、まねぶ「まねる」から来ていると聞くので、色んなよい例を実際にコーディングし、知識や経験を得て
そこから現在作成している勤怠管理システムを、より良いものにしていきたいと思います。
 　
 　
 　
具体的に：
　まずはEntityの連携で社員IDと勤怠情報との連携ができていなのが大きな課題です。
SQLでのInnerJoinやLeftJoinなどは勉強しておりますが、SpringBootではまた違った知識でもあり
実際に自分の技術として扱うにはまだまだ知識が足りない。
そこができれば張りぼての箇所をDBから参照して反映できる仕組みに置き換えることができると考えています。
 　
 　
 　
以上が現時点での私の視覚的にお見せできる技術となっております。
お時間があればソースコードもご確認いただけると幸いです。
 
ご覧いただき誠にありがとうございました。
 
 
 
 
 
 
 
 
 
 
追記：2022年9月20日
 
参考書を基にブラッシュアップをし、下記の内容を実装いたしました。
 
・管理者と一般社員で登録の時に権限を分ける
 
・パスワードを暗号化
 
・入力フォームを、プルダウンなどにしユーザ目線での簡略化
 
・社員検索の機能変更
 
こちらにつきましてはオンラインの際にご希望いただければ
共有画面にて表示いたしますので、
 
お気軽に仰っていただけると幸いです。
