<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inquisitor</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: black;
            color: white;
            text-align: center;
            overflow: hidden;
        }
        #backgroundVideo {
            position: fixed;
            right: 0;
            bottom: 0;
            min-width: 100%; 
            min-height: 100%;
            z-index: -1;
            opacity: 0.2;
        }
        .profile {
            margin-top: 20px;
        }
        .profile img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
        }
        .title {
            font-size: 2.5em;
            font-weight: bold;
        }
        .connections {
            margin-top: 20px;
        }
        .connections a {
            display: block;
            margin: 10px auto;
            width: 200px;
            padding: 10px;
            border: 2px solid white;
            border-radius: 25px;
            color: white;
            text-decoration: none;
            font-size: 1.2em;
            transition: background-color 0.3s;
        }
        .connections a:hover {
            background-color: gray;
        }

    </style>
</head>
<body>
<script>
    document.addEventListener('click', function() {
        var video = document.getElementById('backgroundVideo');
        video.muted = false;
        video.play();
    });
</script>
<body>
    <div class="profile">
        <img src="order_of_fallen_archangels.png" alt="Profile Image">
        <div class="title">Everywhere</div>
        <h2>Inquisitor</h2>
        <p>Owner @oninquisitor</p>
    </div>

    <!-- Connections Section -->
    <div class="connections">
        <a href="https://t.me/inquisitor_adapter" target="_blank">Telegram</a>
        <a href="https://discord.gg/Tn2QB9fd" target="_blank">Discord</a>
        <a href="https://www.reddit.com/u/inquisitorul/s/wXWzDBFzbr" target="_blank">Reddit</a>
        <a href="https://github.com/inquisitor731" target="_blank">GitHub</a>

    </div>

</body>
</html>
