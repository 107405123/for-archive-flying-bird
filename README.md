# for-archive-flying-bird

<html>

<head>
    <style>
       @keyframes flying {
          0% {
                transform: translateX(0px)
            }

        100% {
               transform: translateX(-708px)
            }
        } 

        .bird-flying-block{
            width: 70px;
            height: 100px;
            overflow:hidden;
        }

        .bird{
            animation-name: flying;
            animation-duration: 1s;
            /*animation-fill-mode: both;*/
            animation-iteration-count: infinite;
            /*animation-direction: normal;*/

            animation-timing-function: steps(10, end);
        }
    </style>
</head>

<body>
    <div class="bird-flying-block">
        <img class="bird" height="100px" src="http://raw.githubsercontent,.com/nickhsine/teach-at-nccu/master/assets/image/bird-animation-steps.svg">
    </div>
</body>

</html>
