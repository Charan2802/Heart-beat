# Heart-beat
<!DOCTYPE html>
<html>
    <head>
        <title> animation</title>
        <style>
            body{
                background-color: aliceblue;
                  display: flex;
                  justify-content: center;
                  align-items: center;
                  height:100vh;
            }
            .Heart{
                font-size: 200px;
                animation: heart 0.3s infinite alternate linear;
            }
            @keyframes heart{
                from {
                      transform: scale(0.7);
                }
                t0 {
                      transform:scale(1);
                }
                
            }
        </style>
    </head>
    <body>
        <div class="Heart">❤️</div>
    </body>
</html>
