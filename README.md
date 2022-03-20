# 39FoodDeliveryWebsite
Food Delivery Website Created using purely HTML AND CSS
<!DOCTYPhtml>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Best Food Delivery service In India| AazadMeal.com</title>
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" media="screen and (max-width:1345px)"  href="phone.css">
    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Bree+Serif&display=swap" rel="stylesheet">
</head>

<body>

    <nav id="navbar">
        <div id="logo">
            <img src="logo.png" alt="Meal.com">
        </div>
        <ul>
            <li class="item"><a href="#">Home</a></li>
            <li class="item"><a href="#">Services</a></li>
            <li class="item"><a href="#">About Us</a></li>
            <li class="item"><a href="#">Contact Us</a></li>
            <li class="item"><a href="#">Know Us</a></li>
        </ul>
    </nav>
    <section id="home">
        <h1 class="h-primary">Welcome to AazadMeal.com</h1>
        <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Vitae, facilis ad sed consequuntur nulla ratione
            voluptatem, asperiores qui ducimus voluptate exercitationem libero error unde hic minus laboriosam
            dignissimos quos iusto ipsum earum officiis provident delectus.</p>
        <button class="btn">Order Food</button>
    </section>
    <section id="services-container">
        <h1 class="h-primary center">Our Services</h1>
        <div id="services">
            <div class="box">
                <img src="1.jpg" alt="AazadMeal.com">
                <h2 class="h-secondary">Food Ordering</h2>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea vero asperiores, fugiat molestias
                    blanditiis a nostrum facilis reprehenderit neque, animi alias omnis repudiandae quod in autem
                    earum aliquid quis quos repellat perferendis accusamus exercitationem?</p>
            </div>
            <div class="box">
                <img src="2.jpg" alt="AazadMeal.com">
                <h2 class="h-secondary">Bulk Ordering</h2>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea vero asperiores, fugiat molestias
                    blanditiis a nostrum facilis reprehenderit neque, animi alias omnis repudiandae quod in autem
                    earum aliquid quis quos repellat perferendis accusamus exercitationem?</p>
            </div>
            <div class="box">
                <img src="3.jpg" alt="AazadMeal.com">
                <h2 class="h-secondary">Food Delivery</h2>
                <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Ea vero asperiores, fugiat molestias
                    blanditiis a nostrum facilis reprehenderit neque, animi alias omnis repudiandae quod in autem
                    earum aliquid quis quos repellat perferendis accusamus exercitationem?</p>
            </div>
        </div>
    </section>
    <section id="client-section">
        <h1 class="h-primary center">Our Clients</h1>
        <div id="clients">
            <div class="clients-item">
                <img src="fb.jpg" alt="">
            </div>
            <div class="clients-item">
                <img src="apple.jpg" alt="">
            </div>
            <div class="clients-item">
                <img src="bg2.jpg" alt="">
            </div>
            <div class="clients-item">
                <img src="img.jpg" alt="">
            </div>
        </div>
    </section>
    <section id="contact">
        <div class="h-primary center">Contact Us</div>
        <div id="contact-box">
            <form action="">
                <div class="form-group">
                    <label for="Name">Name:</label>
                    <input type="text" name="name" id="name" placeholder="Enter Your Name">
                </div>
                <div class="form-group">
                    <label for="Name">Email:</label>
                    <input type="email" name="name" id="email" placeholder="Enter your Email Id">
                </div>
                <div class="form-group">
                    <label for="Name">Phone Number:</label>
                    <input type="text" name="name" id="phone" placeholder="Enter your Phone Number">
                </div>
                <div class="form-group">
                    <label for="Name">Message:</label>
                    <textarea name="message" id="message" cols="30" rows="10"></textarea>
                </div>
            </form>
        </div>
    </section>
    <footer>
        <div class="center">
            copyright &copy;www.AazadMeal.com. All Right Reserved 
        </div>
    </footer>
</body>

</html>
