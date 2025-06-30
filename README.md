<!doctype html> 
<html>
    <head>
        <!-- Required meta tags -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
        <!-- Bootstrap CSS -->
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.0.0/dist/css/bootstrap.min.css" integrity="sha384- Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
        <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>
        <!-- jquery -->
        <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.7.0/jquery.min.js" integrity="sha512-3gJwYpMe3QewGELv8k/BX9vcqhryRdzRMxVfq6ngyWXwo03GFEzjsUm8Q7RZcHPHksttq7/GFoxjCVUjkjvPdw==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
        <!--External CSS-->
        <link rel="stylesheet" type="text/css" href="./style.css">
        <!--Internal CSS-->
        <style>
            /* reducing the size of the card and upon hovering increasing the size of the card*/
            .card{
                transform: scale(0.9);
                
            }
            .card:hover{
                transform: scale(1);
            }
        </style>
        
        <title>Shopify</title> 
        
    </head>
    <body class="bg-img container-fluid">
        <!-- dynamically loading header.html using jquery using id -->
        <div id="header"></div>

        <!--backdrop of the application and text upon the background image-->
        <div class="shop container-fluid ">
            <h2 class="slogan" style="font-size: 50px;">"SHOPIFY"<br>Destination for Styles</h2>
        </div>
        <br>

        <!-- carousel -->
        <div class="container-fluid">
            <!-- 2 columns in order write heading and icons for carousels-->
            <div class="row">
                <div class="col-lg-8 col-md-8 col-sm-8">
                    <h2>Featured Products</h2>
                </div>
                <div class="col-lg-4 col-md-4 col-sm-4">
                    <!-- carousel arrow icons for navigation. use of data-bs-target inorder to target the id Mycarousel.-->
                    <button class="carousel-control-prev" type="button" data-bs-target="#Mycarousel" data-bs-slide="prev">
                        <span class="carousel-control-prev-icon"></span>
                    </button>
                    <button class="carousel-control-next" type="button" data-bs-target="#Mycarousel" data-bs-slide="next">
                        <span class="carousel-control-next-icon"></span>
                    </button>
                  
                </div>
            </div>
            <!-- carousel slide classes helps in creating the carousels -->
            <div id="Mycarousel" class="carousel slide" data-bs-ride="carousel">
                <!-- creation of indicators at the bottom -->
                <div class="carousel-indicators">
                    <button type="button" data-bs-target="#Mycarousel" data-bs-slide-to="0" class="active"></button>
                    <button type="button" data-bs-target="#Mycarousel" data-bs-slide-to="1"></button>
                    <button type="button" data-bs-target="#Mycarousel" data-bs-slide-to="2"></button>
                </div>
                <!-- carousel-inner specifies the start of the carousel blocks-->
                <div class="carousel-inner">
                    <!-- 3 carousels with 4 cards -->
                    <div class="carousel-item active">
                        <!-- use of grids to create 4 columns of cards-->
                        <div class="row">
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail" style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/d1.jpg" height="300px">
                                <h4>Western dress</h4>
                                <p>₹500<br>GRECIILOOKS Western Dresses for Women</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                                </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail" style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);" >
                                <img src="./assets/h1.jpg"  height="300px">
                                <h4>Scott International </h4>
                                <p>₹500<br>Rich Cotton Winter Wear Hooded Sweatshirt for Men'</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/k1.avif" height="300px">
                                <h4>Kurta</h4>
                                <p>₹500<br>Navy Rayon Straight Printed Dress</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/s1.jpg" height="300px">
                                <h4>U.S. POLO ASSN.</h4>
                                <p>₹500<br> U.S. POLO ASSN. Men Shirt</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item">
                        <!-- use of grids to create 4 columns of cards-->
                        <div class="row">
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/d2.jpg" height="300px">
                                <h4>Dress</h4>
                                <p>₹500<br>A-Line Above Knee-Length Dress</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                                </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/s2.jpg"  height="300px">
                                <h4>Dennis Lingo</h4>
                                <p>₹500<br>Men's Cotton Casual Shirt with Spread Collar & Full Sleeves</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/k2.avif" height="300px">
                                <h4>Kurta</h4>
                                <p>₹500<br>Deep Fuchsia Rayon Straight Printed Dress</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/kid2.jpg" height="300px">
                                <h4>Jumpsuit</h4>
                                <p>₹500<br>Kid's white and blue jumpsuit</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                        </div>
                    </div>
                    <div class="carousel-item ">
                        <!-- use of grids to create 4 columns of cards-->
                        <div class="row">
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/wl5.jpg" height="300px">
                                <h4>Lounge Wear</h4>
                                <p>₹500<br>Women's Satin Night Suit Set of Top & Shorts</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                                </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12 text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/ml5.jpg"  height="300px">
                                <h4>Lounge Wear</h4>
                                <p>₹500<br>Men’s Night Suit| Men's Co-ord Set</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/kid5.jpg" height="300px">
                                <h4>Girl's lehenga set</h4>
                                <p>₹500<br>Orange coloured sequenced lehenga set</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                            <div class="col-lg-3 col-md-6 col-sm-12  text-center">
                                <div class="card img-thumbnail"  style="  background-color:lightgoldenrodyellow;backdrop-filter: blur(5px);">
                                <img src="./assets/h5.jpg" height="300px">
                                <h4>Pepe Jeans</h4>
                                <p>₹500<br> Men's Escander Colourblock Zip Thru Hoodie</p>
                                <button class="btn btn-secondary" type="button"><i class="fa fa-cart-plus" ></i> Add to cart</button>
                            </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!-- line break -->
        <br><br>
        <!-- dynamically loading footer.html using jquery using id -->
        <div id="footer"></div>
        
        <!-- dynamically loading header.html & footer.html using jquery using id -->
        <script>
            $(function(){
                $("#header").load("nav/header.html");

                $("#footer").load("nav/footer.html");
            })
        </script>

    </body>
</html>
