<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <link href="style.css" rel="stylesheet">
    <title>m1haylow</title>
</head>
<body>
    <header class="v-header container">
    <div class="fullscreen-video-wrap">
        <video src="Video.mp4" autoplay="true" loop="true" muted="true"></video>
        <script>
            function setHalfVolume() {
                var myAudio = document.getElementById("audio");
                myAudio.volume = 0.3;
            }
        </script>
        
        <audio id="audio" src="Video.mp3" type="audio/mp3" controls preload="auto" autoplay loop onloadeddata="setHalfVolume()">

    </div>
        <div class="header-overlay"></div>
        <div class="header-content">

             <h1 id="Text"></h1> 

            <script type="text/javascript">
                var i=0, text;
                text = "m1haylow";

                function typing() {
                    if(i<text.length){
                        document.getElementById("Text").innerHTML +=text.charAt(i);
                        i++;
                        setTimeout(typing, 80);
                    }
                }
                typing();
            </script>

            <p>пЅ‰пЅЌ пЅ†пЅ‰пЅЋпЅ… ' пј’пЅ‹пј‘пј’ пЅЊпЅ…пЅ‡пЅ‰пЅ” пЅ‚пЅЏпЅ™рџЊ№                                     пЅ’пЅЏпЅ“пЅ… пЅЏпЅ† пЅЃпЅЊпЅЊ пЅ—пЅ‰пЅЋпЅ„ рџЊ№ рџЊ№ рџЊ№ рџЊ№</p>
            <a class="btn" href="https://t.me/m1haylow"><i class="fa fa-telegram"></i>  Telegram</a>
            <a class="btn" href="https://www.instagram.com/m1haylovv"><i class="fa fa-instagram"></i>  Instagram</a>
            <a class="btn" href="https://vk.com/m1haylow"><i class="fa fa-vk"></i>  VK</a>
        </div>
    
    </header>

</body>
</html>
