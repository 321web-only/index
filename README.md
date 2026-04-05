<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <title>イベント案内ページ</title>
  <style>
    body {
      font-family: "Hiragino Kaku Gothic ProN", sans-serif;
      background-color: #fdf6f9;
      margin: 0;
      padding: 0;
      color: #555;
    }

    header {
      background: #ffd1dc;
      padding: 30px;
      text-align: center;
    }

    header h1 {
      margin: 0;
      color: #6b4c57;
    }

    .container {
      width: 90%;
      max-width: 800px;
      margin: 30px auto;
    }

    section {
      background: #ffffff;
      border-radius: 15px;
      padding: 20px;
      margin-bottom: 20px;
      box-shadow: 0 4px 10px rgba(0,0,0,0.05);
    }

    h2 {
      color: #7a9cc6;
      border-bottom: 2px solid #e0eafc;
      padding-bottom: 5px;
    }

    .event-info p {
      margin: 8px 0;
    }

    .plan-list {
      list-style: none;
      padding: 0;
    }

    .plan-list li {
      background: #e6f7ff;
      margin: 10px 0;
      padding: 10px;
      border-radius: 10px;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #f8e1f4;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>

  <header>
    <h1>イベントタイトル</h1>
    <p>ここにイベントのキャッチコピーが入ります</p>
  </header>

  <div class="container">

    <!-- 開催概要 -->
    <section class="event-info">
      <h2>開催概要</h2>
      <p>日時：20XX年XX月XX日 XX:XX〜</p>
      <p>場所：オンライン開催</p>
      <p>参加費：無料</p>
      <p>
        ここにイベントの説明が入ります。ダミーテキストです。ここにイベントの説明が入ります。
        ここにイベントの説明が入ります。ここにイベントの説明が入ります。
      </p>
    </section>

    <!-- 企画内容 -->
    <section>
      <h2>企画内容</h2>
      <ul class="plan-list">
        <li>
          <strong>企画1：</strong>
          ダミーテキストです。ここに企画内容の説明が入ります。
        </li>
        <li>
          <strong>企画2：</strong>
          ダミーテキストです。ここに企画内容の説明が入ります。
        </li>
        <li>
          <strong>企画3：</strong>
          ダミーテキストです。ここに企画内容の説明が入ります。
        </li>
      </ul>
    </section>

  </div>

  <footer>
    © 20XX Event Project
  </footer>

</body>
</html>
