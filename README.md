flexbox

<!DOCTYPE html>
<html>
    <head>
        <title>Flex and Grid Example</title>
        <style>
            body{
                font-family: Arial;
                margin:0 ;
            }
            header{
                background-color: skyblue;
                padding:15px;
                display: flex;
                justify-content: center;
                align-items: center;

            }
            grid-container{
                display: grid;
                grid-template-columns:1fr 2fr 1fr;
                gap: 10px;
                padding: 10px;

            }

            .box{
                background-color: lightgray;
                  padding: 20px;
                  text-align: center;
            }
            footer{
                background-color: lightgreen;
                padding: 10px;
                display: flex;
                justify-content: center;

            }
        </style>

    </head>
    <header>
        <h2>
            My Web Layout using Flexbox and Grid
        </h2>
    </header>
    <div class="grid-container">
        <div class="box">Left Panel</div>
        <div class="box">Main Content Area</div>
        <div class="box">Right Panel</div>
    </div>
    <footer>
        <p>
            Footer Section
        </p>
    </footer>
</body>
    
</html>




media queries

<!DOCTYPE html>
<html>
    <head>
        <title>Responsive Web Design Example</title>
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <style>
            body{
                font-family:Arial;
                text-align: center;
                padding: 20px;
            }
            .box{
                background-color: lightblue;
                padding: 20px;
                font-size: 24px;
            }
            @media (max-width: 768px) {
                .box {
                    background-color: lightgreen;
                    font-size: 20px;
                }
            }
            @media (max-width: 480px) {
                .box {
                    background-color: orange;
                    font-size: 18px;
                }
            }
        </style>
    </head>
    <body>
        <h1>Responsive Web Design</h1>
        <div class="box">
            Resize the browser window to see the background color and font size change!
        </div>
    </body>
</html>


