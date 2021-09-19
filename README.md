Skip to content
Search or jump to…
Pull requests
Issues
Marketplace
Explore
 
@tirolenitin 
tirolenitin
/
LGMVIP-Webdevelopment_1st
Public
1
0
0
Code
Issues
Pull requests
Actions
Projects
Wiki
Security
Insights
Settings
LGMVIP-Webdevelopment_1st/lgm_1st/index.html
@tirolenitin
tirolenitin Add files via upload
…
Latest commit 00b2c6d 16 minutes ago
 History
 1 contributor
302 lines (280 sloc)  12.4 KB
  
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Sweet Spot</title>
    <link rel="stylesheet" href="css/style1.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
</head>
<body>
    <header class="header">

        <a href="#" class="logo">
            <img src="img/CakesBakery1.png" alt="">
        </a>

        <nav class="navbar " id="navbar">
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#menu">Menu</a>
            <a href="#product">Product</a>
            <a href="#review">Review</a>
            <a href="#contactus">Contact Us</a>
        </nav>

        <div class="icons">
            <div class="fas fa-search" id="search-btn"></div>
            <div class="fas fa-shopping-cart" id="cart-btn"></div>
            <div class="fas fa-bars" id="menu-btn" ></div>

        </div>

        <div class="search-form">
            <input type="search"  id="search-box" 
            placeholder="search here...">
            <label for="search-box" class="fas fa-search"></label>
        </div>
        <div class="cart-items-container" id="cart-items">
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="img/product1.jpg" alt="">
                <div class="content">
                    <h3>cart item 01</h3>
                    <div class="price">115/- &#x20B9</div>
                </div>
            </div>
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="img/product1.jpg" alt="">
                <div class="content">
                    <h3>cart item 02</h3>
                    <div class="price">100/- &#x20B9</div>
                </div>
            </div>
            <div class="cart-item">
                <span class="fas fa-times"></span>
                <img src="img/product1.jpg" alt="">
                <div class="content">
                    <h3>cart item 03</h3>
                    <div class="price">50/- &#x20B9</div>
                </div>
            </div>
            <a href="#" class="btn">checkout now</a>
        </div>
    </header>
    <section class="home " id="home">
        <div class="content">
            <h3>Fresh cake are available 24*7</h3>
            <p>Lorem  officia inventore, quasi commodi, optio aliquid exercitationem libero aliquam porro minus labore sequi recusandae?</p>
            <a href="#" class="btn">Get your order</a>
        </div>
    </section>

    <section class="about" id="about">
        <h1 class="heading"><span>about </span>  us</h1>
        <div class="row">
            <div class="image">
                <img src="img/cake2.jpg" alt="">
            </div>
            <div class="content">
                <h3>What makes our bakery special</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quibusdam nemo explicabo maxime facere! Expedita sed, molest</p>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsam, possimus. Minus quod consequuntur aliquam, enim accus</p>
                <a href="#" class="btn">learn more</a>
            </div>
        </div>
    </section>

     <section class="menu" id="menu">
        <h1 class="heading">our <span> menu </span></h1>
        <div class="box-container">
            <div class="box">
                <img src="img/menu-2.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
            <div class="box">
                <img src="img/menu-3.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
            <div class="box">
                <img src="img/menu-4.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
            <div class="box">
                <img src="img/menu-5.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
            <div class="box">
                <img src="img/menu-6.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
            <div class="box">
                <img src="img/menu-7.jpg" alt="">
                <h3>Tasty and Delicious</h3>
                <div class="price">200 &#x20B9</div>
                <a href="#" class="btn ">add to cart</a>
            </div>
        </div>
    </section>

    <section class="products" id="product">
        <h1 class="heading">our <span> products </span></h1>
        <div class="box-container">
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="img/product1.jpg" alt="">
                </div>
                <div class="content">
                    <h3>fresh cake</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">250 &#x20B9  </div>
                </div>
            </div>
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="img/product2.jpg" alt="">
                </div>
                <div class="content">
                    <h3>fresh cake</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">250 &#x20B9  </div>
                </div>
            </div>
            <div class="box">
                <div class="icons">
                    <a href="#" class="fas fa-shopping-cart"></a>
                    <a href="#" class="fas fa-heart"></a>
                    <a href="#" class="fas fa-eye"></a>
                </div>
                <div class="image">
                    <img src="img/product3.jpg" alt="">
                </div>
                <div class="content">
                    <h3>fresh cake</h3>
                    <div class="stars">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                    <div class="price">250 &#x20B9  </div>
                </div>
            </div>
        </div>
    </section>
    <section class="review" id="review">
        <h1 class="heading">costomer's <span>review</span></h1>
        <div class="box-container">
            <div class="box">
                <img src="img/quote-img.png" alt="" class="qoute">
                <p>Lorem ipsum dolor sit amet Loreima facilis optio laudantium, ad voluptas officiis maxime ipsa hic assumenda! Molestias.
                consectetur, adipisicing elit. Nostrum, error deleniti sint in</p>
                <img src="img/vicky.jpg" alt="" class="user">
                <h3>vicky karma</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            <div class="box">
                <img src="img/quote-img.png" alt="" class="qoute">
                <p>Lorem ipsum dolor sit amet Loreima facilis optio laudantium, ad voluptas officiis maxime ipsa hic assumenda! Molestias.
                consectetur, adipisicing elit. Nostrum, error deleniti sint in</p>
                <img src="img/vikas.jpg" alt="" class="user">
                <h3>richa singh</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
            <div class="box">
                <img src="img/quote-img.png" alt="" class="qoute">
                <p>Lorem ipsum dolor sit amet Loreima facilis optio laudantium, ad voluptas officiis maxime ipsa hic assumenda! Molestias.
                consectetur, adipisicing elit. Nostrum, error deleniti sint in</p>
                <img src="img/yash.jpg" alt="" class="user">
                <h3>yash rane</h3>
                <div class="stars">
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star"></i>
                    <i class="fas fa-star-half-alt"></i>
                </div>
            </div>
        </div>
    </section>

    <section class="contact" id="contactus">
        <h1 class="heading"><span>contact</span> us</h1>
        <div class="row">
              <iframe class="map" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3679.1607398201313!2d75.85163031479567!3d22.759415285086977!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x39630287fdfa5b2b%3A0xe221d61e19da3a2e!2sSector%20D%20Rd%2C%20Sector%20D%2C%20Sanwer%20Road%20Industrial%20Area%2C%20Indore%2C%20Madhya%20Pradesh%20452003!5e0!3m2!1sen!2sin!4v1631939541509!5m2!1sen!2sin"  allowfullscreen="" loading="lazy"></iframe>

        
            <form action="">
                <h3>get in touch</h3>
                <div class="inputBox">
                    <span class="fas fa-user"></span>
                    <input type="text" placeholder="name">
                </div>
                <div class="inputBox">
                    <span class="fas fa-envelope"></span>
                    <input type="email" placeholder="email">
                </div>
                <div class="inputBox">
                    <span class="fas fa-phone"></span>
                    <input type="number" placeholder="number">
                </div>
                <input type="submin" class="btn" value=" contact now">
            </form>
        </div>
    </section>

    <section class="footer">
        <div class="share">
            <a href="#" class="fab fa-facebook-f"></a>
            <a href="#" class="fab fa-twitter"></a>
            <a href="#" class="fab fa-instagram"></a>
            <a href="#" class="fab fa-linkedin"></a>
        </div>
        <div class="links">
            <a href="#">home</a>
            <a href="#">about</a>
            <a href="#">menu</a>
            <a href="#">products</a>
            <a href="#">review</a>
            <a href="#">contactus</a>
        </div>
        <div class="credit"> &copy; all right are reserved</div>
    </section>








<script src="js/app.js"></script>


</body>
</html>

