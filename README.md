  <!DOCTYPE html>
    <html lang="en">

    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width= device-width, initial-scale=1.0">
        <meta http-equiv="X-UA-compatible" content="ie=edge">
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=Montserrat:ital@0;1&family=Poppins&display=swap" rel="stylesheet">
        <link rel="stylesheet" type="text/css" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
        <style>
            *,
            body {
                margin: 0px;
                font-family: 'Montserrant', sans-serif;

            }

            body {
                width: 100%;
                height: 100%;
                background-color: rgb(24, 23, 30);
            }

            .image-container {
                width: 100%;
                height: 400px;

            }

            #image {
                display: flex;
                float: left;
                background-color: rgb(226, 219, 221);
                width: 30%;
                height: 400px;
                margin-top: 10px;
                margin-left: 25px;
                border-radius: 0px;
            }

            img {
                width: 200px;
                height: 200px;
                margin-left: 125px;
                margin-top: 10px;
                border-radius:20px ;


            }

            #image:hover {
                background-color: rgb(162, 230, 16);
                border-radius: 50px;
                transition: 4s;
            }

            a {
                color: red;
                font-size: 40px border-radius:10px;
                text-decoration:none;
                
            }
            
            h1 {
                text-align: center;
                color:brown;
                font-size: 10px;
                margin-top: 15px;

            }
            
            button{
                background-color: blue;
                font-size: 35px;
                border: 2px solid black;
                border-radius: 10px;
                margin-top: 8px;
            }
            button:hover{
                background-color: rgb(244, 54, 200);
                border: 2px solid rgb(206, 199, 199);
            }
            .description{
                width: 100%;
                height: 90px;
                background-color: wheat;
                border-radius:20px ;
            }
            p{
                color:rgb(181, 161, 37);
                font-size: 25px;
                
                font-family: 'Times New Roman', Times, serif;
            }
           @media only screen and ( min-width:200px) and (max-width:520px){

            .image-container {
                width: 100%;
                height: 400px;

            }
            #image {
    display: flex;
    float: left;
    background-color: rgb(226, 219, 221);
    width: 100%;
    height: 400%;
    margin-top: 10px;
    margin-left: 5px;
    border-radius: 0px;
            }
            img {
                width:200px;
                height:200px;
                margin-left:100px;
                margin-top: 10px;
                border-radius:20px;
            }
            p{
                color:rgb(181, 161, 37);
                font-size: 20px;
                
                font-family: 'Times New Roman', Times, serif;
            }
            button:hover{
                background-color: rgb(244, 54, 200);
                border: 2px solid rgb(206, 199, 199);
            }
            #image:hover {
                background-color: rgb(162, 230, 16);
                border-radius: 50px;
                transition: 4s;
            }
            }

        </style>
    </head>

    <body>

        <div class="container">
            <div id="image">
                <div class="image-container">
                    <img src="https://m.media-amazon.com/images/I/61LO6l4zB4L._SX679_.jpg" />
                    <div class="description"><p>Read description of the product and purchase this product by clicking on the BUY NOW button.</p></div>
                    <h1>IN ASSOCIATE PARTNERSHIP WITH AMAZON.IN</h1>
                     <div style="text-align: center"><button><a href="https://amzn.to/3VUDSdW">Buy Now</a>
                    </button></div>
                </div>
            </div>
            <div class="container">
                <div id="image">
                    <div class="image-container">
                        <img src="https://m.media-amazon.com/images/I/61LO6l4zB4L._SX679_.jpg" />
                        <div class="description"><p>Read description of the product and purchase this product by clicking on the BUY NOW button.</p></div>
                        <h1>IN ASSOCIATE PARTNERSHIP WITH AMAZON.IN</h1>
                         <div style="text-align: center"><button><a href="https://amzn.to/3VUDSdW">Buy Now</a>
                        </button></div>
                    </div>
                </div>
                <div class="container">
                    <div id="image">
                        <div class="image-container">
                            <img src="https://m.media-amazon.com/images/I/61LO6l4zB4L._SX679_.jpg" />
                            <div class="description"><p>Read description of the product and purchase this product by clicking on the BUY NOW button.</p></div>
                            <h1>IN ASSOCIATE PARTNERSHIP WITH AMAZON.IN</h1>
                             <div style="text-align: center"><button><a href="https://amzn.to/3VUDSdW">Buy Now</a>
                            </button></div>
                        </div>
                    </div>
            
    </body>
    </html>

