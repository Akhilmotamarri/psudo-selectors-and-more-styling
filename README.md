# psudo-selectors-and-more-styling
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>pseudo selectors and more designing</title>
    <style>
        .container{
            border: 2px solid red;
            background-color: rgb(85, 146, 24);
            padding: 34px;
            margin: auto;
            width: 666px;
        }
        a:hover{
            /* border: 2px solid grey; */
            text-decoration:underline hotpink;
            color: indianred;

        }
        a:visited{
            color: rgb(184, 240, 32);
        }
        a:active{
            color: lightcoral;
            background-color: lightskyblue;
        }
        .btn:hover{/* hover to used for mouse click effect*/
            color: rgb(129, 10, 158);
            border: 4px solid rgb(252, 151, 18);
            border-radius: 25px;
            font-family: Georgia, 'Times New Roman', Times, serif;

        }
        button{
            background-color: rgb(85, 110, 250);
        }
    </style>
</head>
<body>
    <div class="container" id="cont1">
        <h3>this is my heading</h3>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Unde dicta rerum temporibus iure asperiores, aspernatur reiciendis perferendis quaerat sint, ducimus laudantium a aliquid incidunt dolores, itaque sequi mollitia in enim voluptatibus consequuntur modi. Eligendi, repellat iure magnam velit, quia at fugit, id sapiente recusandae deleniti animi. Consequatur unde quos praesentium.
            <a href="contact.com" target="_blank"> contact us </a>
            <br>readmore... <button class="btn">
                click here
            </button>
        </p>

    </div>
</body>
</html>
