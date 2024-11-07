<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>私のウェブサイト</title>
    <style>
        body {
            background-color: #1a1a1a;
            color: white;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header {
            text-align: center;
            padding: 50px;
        }
        header h1 {
            font-size: 3em;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.7);
        }
        .content {
            display: flex;
            justify-content: center;
            flex-direction: column;
            align-items: center;
            padding: 20px;
        }
        .song-container {
            margin-top: 20px;
            text-align: center;
        }
        audio {
            width: 100%;
            max-width: 600px;
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <header>
        <h1>私のウェブサイトへようこそ</h1>
        <p>ここに私の好きな音楽があります。</p>
    </header>

    <div class="content">
        <div class="song-container">
            <h2>お気に入りの曲</h2>
            <audio controls>
                <source src="your-song.mp3" type="audio/mpeg">
                お使いのブラウザはaudioタグに対応していません。
            </audio>
        </div>
    </div>
</body>
</html>
