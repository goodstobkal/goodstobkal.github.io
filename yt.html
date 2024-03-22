<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Watch Video</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        #video-container {
            position: relative;
            width: 100%;
            padding-top: 56.25%; /* 16:9 Aspect Ratio (divide 9 by 16 = 0.5625) */
            overflow: hidden;
        }
        #video {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
        }
    </style>
</head>
<body>
    <h1>Watch Video</h1>
    <div id="video-container">
        <iframe id="video" src="https://www.youtube.com/embed/o89xwJdFgyo?enablejsapi=1" frameborder="0" allowfullscreen></iframe>
    </div>
    <p>Duration Watched: <span id="duration-watched">0:00</span></p>

    <script>
        var player;
        var durationWatched = 0;
        var timer;

        function onYouTubeIframeAPIReady() {
            player = new YT.Player('video', {
                events: {
                    'onReady': onPlayerReady,
                    'onStateChange': onPlayerStateChange
                }
            });
        }

        function onPlayerReady(event) {
            event.target.playVideo();
            timer = setInterval(updateDurationWatched, 1000); // Update duration every second
        }

        function onPlayerStateChange(event) {
            if (event.data == YT.PlayerState.ENDED) {
                clearInterval(timer);
            }
        }

        function updateDurationWatched() {
            var currentTime = player.getCurrentTime();
            durationWatched = Math.round(currentTime);
            var minutes = Math.floor(durationWatched / 60);
            var seconds = durationWatched - minutes * 60;
            var formattedTime = minutes.toString().padStart(2, '0') + ':' + seconds.toString().padStart(2, '0');
            document.getElementById('duration-watched').innerText = formattedTime;
        }
    </script>

    <script src="https://www.youtube.com/iframe_api"></script>
</body>
</html>
