!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Display Position In CSS</title>
    <style>
        * {
            box-sizing: border-box;
        }
        .top {
            border: 3px solid red;
            margin: auto;
            width: 1300px;
        }

        img {
            display: block;
            margin: auto;
            width: 70px;
        }

        h3 {
            margin: 0px;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
        }

        .mySpan {
            margin: auto;
            border: 3px solid green;
            width: 1300px;
            text-align: center;
        }

        .mySpan1 {
            margin: 0px auto;
            border: 3px solid darkblue;
            display: block;
            width: 1300px;
            text-align: center;
        }

        .container {
            border: 3px solid red;
            width: 1300px;
            margin: 10px auto;
        }

        .box {
            background-color: bisque;
            border: 3px solid grey;
            margin: 5px 2px;
            padding: 20px;
            display: inline-block;
            width: 420px;
        }
        #box1 {
            margin-left: 8px;
        }
    </style>
</head>

<body>
    <header class="top">
        <img src="https://www.codewithharry.com/_next/image/?url=%2Fimg%2Flogo-blue.png&w=48&q=75" alt="">
        <h3>Welcome to Harry's Blog</h3>
    </header>
    <p class="mySpan">This is a Span Element.</p>
    <span class="mySpan1">This is my span.</span>
    <!-- Inline Elements are not able to center using margin: auto;  
                                                  // Block Elements are able to center using margin: auto; after reducing thier width.-->
    <div class="container">
        <div class="box" id="box1">
            <h4 class="heading">Heading</h4>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores, harum ipsam aliquid deleniti, vitae
                labore cum laudantium a blanditiis est voluptates dolorum consequuntur. Aliquam corporis, fuga
                consectetur rerum molestias consequatur tempora natus sed laborum recusandae fugit harum soluta
                inventore enim. Aspernatur aperiam cum reprehenderit!</p>
        </div>

        <div class="box" id="box2">
            <h4 class="heading">Heading</h4>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores, harum ipsam aliquid deleniti, vitae
                labore cum laudantium a blanditiis est voluptates dolorum consequuntur. Aliquam corporis, fuga
                consectetur rerum molestias consequatur tempora natus sed laborum recusandae fugit harum soluta
                inventore enim. Aspernatur aperiam cum reprehenderit!</p>
        </div>

        <div class="box" id="box3">
            <h4 class="heading">Heading</h4>
            <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Maiores, harum ipsam aliquid deleniti, vitae
                labore cum laudantium a blanditiis est voluptates dolorum consequuntur. Aliquam corporis, fuga
                consectetur rerum molestias consequatur tempora natus sed laborum recusandae fugit harum soluta
                inventore enim. Aspernatur aperiam cum reprehenderit!</p>
        </div>
    </div>
</body>

</html>
