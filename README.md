<!DOCTYPE html>
<html>
	<head>
		<meta charset="utf-8" />
		<title>动态照片墙</title>
		<link rel="stylesheet" href="css/dt.css" />
	</head>
	<body>
		 <div class="box" id="box">
		    <img id="photo1" src="img/1.jpg" alt="Photo 1" onclick="toggleMusic1()"/>
            <img id="photo2" src="img/2.jpg" alt="Photo 2" onclick="toggleMusic2()"/>
            <img id="photo3" src="img/3.jpg" alt="Photo 3" onclick="toggleMusic3()"/>
            <img id="photo4" src="img/4.jpg" alt="Photo 4" onclick="toggleMusic4()"/>
            <img id="photo5" src="img/5.jpg" alt="Photo 5" onclick="toggleMusic5()"/>
            <img id="photo6" src="img/6.jpg" alt="Photo 6" onclick="toggleMusic6()"/>
            <img id="photo7" src="img/7.jpg" alt="Photo 7" onclick="toggleMusic7()"/>
            <img id="photo8" src="img/8.jpg" alt="Photo 8" onclick="toggleMusic8()"/>

            
            <audio id="musicPlayer1" src="img/1.1.mp3" preload="auto"></audio> 
            <audio id="musicPlayer2" src="img/2.2.mp3" preload="auto"></audio> 
            <audio id="musicPlayer3" src="img/3.3.mp3" preload="auto"></audio> 
            <audio id="musicPlayer4" src="img/4.4.mp3" preload="auto"></audio>
            <audio id="musicPlayer5" src="img/5.5.mp3" preload="auto"></audio>
            <audio id="musicPlayer6" src="img/6.6.mp3" preload="auto"></audio> 
            <audio id="musicPlayer7" src="img/7.7.mp3" preload="auto"></audio> 
            <audio id="musicPlayer8" src="img/8.8.mp3" preload="auto"></audio> 
  
    <script src="js/script.js"></script>
    </div>
	</body>
</html>
ml…]()

[Uploading sfunction toggleMusic1() {
            var audio = document.getElementById('musicPlayer1');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic2() {
            var audio = document.getElementById('musicPlayer2');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic3() {
            var audio = document.getElementById('musicPlayer3');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic4() {
            var audio = document.getElementById('musicPlayer4');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic5() {
            var audio = document.getElementById('musicPlayer5');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic6() {
            var audio = document.getElementById('musicPlayer6');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic7() {
            var audio = document.getElementById('musicPlayer7');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }

        function toggleMusic8() {
            var audio = document.getElementById('musicPlayer8');
            if (audio.paused) {
                audio.play();
            } else {
                audio.pause();
            }
        }cript.js…]()
[Uploading dt.css…]()div img:nth-child(odd){
     width: 300px;
     }
div img:nth-child(even){
    width:100px;
    }
.box{
    width: 960px;
    margin:200px auto;
    position: relative;
    
    }
.box img{
    border:1px solid #DDDDDD;
    padding:10px;
    background-color:#fff;
    position:absolute;
    z-index:1;
    transition: all 0.6s ease-in-out;
    box-shadow: 5px 5px 5px pink;
      }

        #box img:hover{
            transform: rotate(0deg) scale(1.5);
            z-index:2;
            box-shadow: 5px 5px 5px pink;
        }
        
        /* 移动端样式 */
@media screen and (max-width: 600px) {
    .box img {
        width: 80%; /* 减小宽度以适应小屏幕 */
        max-width: none; /* 移除最大宽度限制 */
    }
    
    .box img:nth-child(1),
    .box img:nth-child(2),
    .box img:nth-child(3),
    .box img:nth-child(4),
    .box img:nth-child(5),
    .box img:nth-child(6),
    .box img:nth-child(7),
    .box img:nth-child(8) {
        top: auto;
        left: 50%;
        transform: translateX(-50%) rotate(0deg); /* 居中并取消旋转 */
        margin-bottom: 20px; /* 添加底部间距 */
    }
}

        .box img:nth-child(1) {
            top: 0px;
            left: 300px;
            transform: rotate(-15deg);
        }

        .box img:nth-child(2) {
            width: 180px;
             top: 0px;
            left: 600px;
            transform: rotate(-20deg);
        }

        .box img:nth-child(3) {
            bottom:-80px;
            right: 0;
            transform: rotate(15deg);
        }

        .box img:nth-child(4) {
            width: 140px;
            bottom: -30px;
            left: 460px;
            transform: rotate(-20deg);
        }

        .box img:nth-child(5) {
            bottom: -300px;
            left: -400;
            transform: rotate(-30deg);
        }

        .box img:nth-child(6) {
            width: 180px;
            top: 0;
            left: 400;
            transform: rotate(20deg);
        }

        .box img:nth-child(7) {
            top: -150;
            left: 700px;
            transform: rotate(20deg);
        }

        .box img:nth-child(8) {
            width: 140px;
            height: 170px;
            bottom: -20px;
            right: 550px;
            transform: rotate(30deg);
        }

