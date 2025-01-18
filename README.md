# mysite
<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ポートフォリオ</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    /* カラーテーマ */
    :root {
      --primary-color: #4a4a4a; /* テキストの濃いグレー */
      --secondary-color: #ffecec; /* 背景の淡いピンク */
      --accent-color: rgb(238, 164, 164); /* 強調用の赤みがかったピンク */
      --card-background: #ffffff; /* カードの背景色 */
      --card-border: #ffcdd2; /* カードの境界色 */
    }

    body {
      background-color: var(--secondary-color);
      color: var(--primary-color);
      font-family: 'Roboto', sans-serif;
      line-height: 1.6;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: var(--accent-color);
      color: white;
      padding: 1em 2em;
      text-align: center;
      border-bottom: 4px solid var(--card-border);
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    main {
      max-width: 900px;
      margin: 2em auto;
      padding: 1em;
    }

    h2 {
      color: var(--primary-color);
      font-weight: 700;
      margin-top: 2em;
      margin-bottom: 0.5em;
      border-bottom: 2px solid var(--card-border);
      padding-bottom: 0.2em;
    }

    .card {
      background-color: var(--card-background);
      border: 1px solid var(--card-border);
      border-radius: 12px;
      padding: 1.5em;
      margin: 1em 0;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
    }

    .card h3 {
      margin-top: 0;
      color: var(--primary-color);
    }

    .card p {
      color: #555;
    }

    .card a {
      color: var(--accent-color);
      text-decoration: none;
      font-weight: bold;
    }

    .card a:hover {
      text-decoration: underline;
    }

    a {
      color: var(--accent-color);
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      text-decoration: underline;
    }

    @media (max-width: 768px) {
      body {
        margin: 0 1em;
      }

      h1 {
        font-size: 2rem;
      }

      h2 {
        font-size: 1.5rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>ポートフォリオ</h1>
  </header>
  <main>
    <article id="main" class="page sans">
      <div class="page-body">
        <h2 id="learning-history">■学習履歴</h2>
        <div class="card">
          <h3>職業訓練校</h3>
          <p>2024/7～25/1までJava・Web技術科にてプログラム学習開始</p>
        </div>
        <div class="card">
          <h3>資格取得</h3>
          <p>2024/11 Oracle JAVA Silver取得</p>
        </div>

        <h2 id="learning-book">■学習書籍・資料</h2>
        <div class="card">
          <ul>
            <li><a href="https://amzn.asia/d/7RkE2D1">スッキリわかるJava入門 第４版</a></li>
            <li><a href="https://amzn.asia/d/0DpoZD2">スッキリわかるJava入門 実践編 第４版</a></li>
            <li><a href="https://amzn.asia/d/g1XNmQ1">書き込み式SQLのドリル 改訂新版</a></li>
            <li><a href="https://amzn.asia/d/fdC1m9I">基礎からのサーブレット/JSP 第５版</a></li>
            <li><a href="https://amzn.asia/d/aUqhAVP">改訂新版SpringFramework超入門やさしくわかるWeb</a></li>
            <li>（学校独自資料）JavaScript基礎応用</li>
            <li>（学校独自資料）HTML・CSS基礎応用</li>
          </ul>
        </div>

        <h2 id="self-learning">■自己学習</h2>
        <div class="card">
          <ul>
            <li><a href="https://amzn.asia/d/36M5AAm">徹底攻略JavaSilver問題集</a></li>
            <li><a href="https://amzn.asia/d/0kUtUhp">CleanArchitecture達人に学ぶソフトウェア構造と設計</a></li>
            <li><a href="https://amzn.asia/d/cYeHCdi">リーダブルコード ―より良いコードを書くためのシンプルで実践的なテクニック </a></li>
            <li>Paizaラーニング - Bランク取得</li>
            <li>Atcoder  - EASY/NOMALランクはほぼ回答可能、HARDは一部のみ回答可能</li>
          </ul>
        </div>
	  
        <h2 id="tool">■使用可能ツール</h2>
        <div class="card">
          <ul>
            <li><a href="https://eclipseide.org/">Eclipse</a></li>
            <li><a href="https://forest.watch.impress.co.jp/library/software/heidisql/">HeidiSQL</a></li>
            <li><a href="https://spring.io/tools">SpringToolSuite</a></li>
          </ul>
        </div>
		
        <h2 id="skill">■技術スタック</h2>
        <div class="card">
          <ul>
            <li>フロントエンド: HTML5, CSS3, JavaScript, Bootstrap</li>
            <li>バックエンド: Java, Spring Framework, Servlet/JSP</li>
            <li>データベース: MySQL</li>
            <li>開発ツール: Eclipse, Spring Tool Suite, Git</li>
          </ul>
        </div>
		
        <h2 id="created">■作成物</h2>
        <div class="card">
          <h3>1.ショッピングECサイト</h3>
          <p>Java、Servlet/JSP、MySQLを使用したECサイトアプリケーション。</p>
          <ul>
            <li>商品の検索、カート機能、注文履歴の管理機能を実装</li>
            <li>MySQLデータベースを用いたログイン認証システム</li>
            <li>バリデーションを活用した新規ID作成機能</li>
            <li>データベース第２正規化により注文履歴管理やデータベースの効率化を実現</li>
          </ul>
          <a href="#">コードを見る</a>
        </div>
		
        <div class="card">
          <h3>2.タスク管理アプリケーション</h3>
          <p>Spring Framework、MySQLを使用したタスク管理Webアプリケーション。</p>
          <ul>
            <li>タスクの作成、編集、削除機能</li>
            <li>優先度設定と期限管理機能</li>
            <li>JavaScriptを使用した動的なモーダルウィンドウUI実装</li>
            <li>独自アノテーション作成活用</li>
          </ul>
		  
          <a href="https://github.com/ogawa-sakura/tasklist">コードを見る</a>
        </div>
        <div class="card">
          <h3>3.社員名簿管理アプリケーション</h3>
          <p>Spring Framework、Bootstrapを使用した社員名簿管理Webアプリケーション。</p>
          <ul>
            <li>社員IDの作成、削除機能</li>
            <li>Bootstrapを使用した動的なUI実装</li>
            <li>※Bootstrapのテストのため簡易的な実装です</li>
          </ul>
          <a href="https://github.com/ogawa-sakura/store">コードを見る</a>
        </div>
      </div>
    </article>
  </main>
</body>
</html>
