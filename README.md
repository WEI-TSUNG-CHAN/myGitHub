<!DOCTYPE html>
<html lang="zh-Hant">
<head>
  <meta charset="UTF-8">
  <meta name="google-adsense-account" content="ca-pub-2700712381606881">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>小遊戲</title>
  <style>
    /* 设置页面的基础样式 */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    h1 {
      text-align: center;
      margin-top: 20px;
    }
    /* 视频容器样式 */
    .video-container {
      position: relative;
      width: 100%;
      padding-bottom: 56.25%; /* 保持16:9宽高比 */
      height: 0;
      overflow: hidden;
      background: #000;
      margin: 20px 0;
    }
    .video-container iframe {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
    }
    /* 游戏链接样式 */
    .container {
      width: 90%;
      margin: 0 auto;
      padding: 20px;
    }
    .game-link {
      margin: 10px 0;
      text-align: center;
    }
    .game-link a {
      display: inline-block;
      padding: 10px 20px;
      background-color: #007bff;
      color: white;
      text-decoration: none;
      border-radius: 5px;
    }
    .game-link a:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <h1>小遊戲</h1>

  <div class="container">
    <div class="game-link">
      <a href="klotski-game/version5x5/index.html">華容道</a>
    </div>
    <div class="game-link">
      <a href="Tetris-game-v1/index.html">俄羅斯方塊</a>
    </div>
    <div class="game-link">
      <a href="chtguess-game/index.html">中文字寫練習(手機)</a>
    </div>
    <!-- 嵌入YouTube视频 -->
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/i7vKBM8397I" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/TQooyM9kOuc" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
    <div class="video-container">
      <iframe src="https://www.youtube.com/embed/xIbq_hbQQok" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
    </div>
  </div>

</body>
</html>
