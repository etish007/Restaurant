<!DOCTYPE html>
<html>

<head>
    <title>Restaurant Website</title>
    <style>
        /* CSS styles for your restaurant website */
        body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    color: #333;
    background-color: #f9f9f9;
}

header {
    text-align: center;
    padding: 20px;
    width: 100%;
    background-color: #333;
    color: #fff;
}

main {
    max-width: 800px;
    margin: 40px auto;
    width: 90%;
}

h1 {
    font-size: 36px;
    margin-bottom: 20px;
    text-align: center;
}

h2, h3 {
    font-size: 24px;
    margin-bottom: 10px;
    text-align: left;
}

p, ul {
    margin-bottom: 20px;
    text-align: left;
}

ul {
    list-style-type: disc;
    padding-left: 20px;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    width: 100%;
    color: #fff;
}

footer p {
    margin: 0;
    font-size: 14px;
    text-align: center;
}

.location {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    margin-top: 20px;
}

.location img {
    width: 30px;
    height: 30px;
    margin-right: 10px;
}

.social-icons {
    display: flex;
    align-items: center;
    justify-content: flex-start;
    margin-top: 20px;
}

.social-icons a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-color: white;
    border-radius: 50%;
    margin-right: 10px;
}

.social-icons a:last-child {
    margin-right: 0;
}

.social-icons img {
    width: 20px;
    height: 20px;
}

.contact-info {
    margin-top: 40px;
    text-align: center;
}

.contact-info p {
    margin-bottom: 10px;
}

.image-gallery {
    display: flex;
    justify-content: space-between;
    margin-top: 20px;
}
.contact-info {
    margin-top: 40px;
    text-align: center;
}

.contact-info p {
    margin-bottom: 10px;
}

.location-social {
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 20px;
}

.location-social a {
    display: flex;
    align-items: center;
    justify-content: center;
    width: 40px;
    height: 40px;
    background-color: white;
    border-radius: 50%;
    margin-right: 10px;
}

.location-social a:last-child {
    margin-right: 0;
}

.location-social img {
    width: 30px;
    height: 30px;
    margin-right: 10px;
}
.image-gallery img {
    width: 200px;
    height: auto;
    border-radius: 10px;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    margin-right: 10px;
}

.image-gallery img:last-child {
    margin-right: 0;
}
    </style>
</head>

<body>
    <header>
        <h1>Welcome to Night Star Restaurant</h1>
        <img src="\RESOURCES\NIGHT STAR.png" alt="Restaurant Image">
    </header>

    <main>
        <section>
            <h2>About Us</h2>
            <p>Welcome to Night Star Restaurant, your ultimate destination for exquisite dining experiences. Located at our charming venue, we take pride in offering top-notch service and serving delicious, mouthwatering dishes that will tantalize your taste buds.</p>
    
            <p>At Night Star Restaurant, we are dedicated to providing exceptional hospitality, ensuring that every guest feels warmly welcomed and pampered. Our professional staff is committed to delivering personalized service, catering to your every need to ensure an unforgettable dining experience.</p>
    
            <p>Indulge in our diverse menu that showcases a fusion of flavors, prepared with the finest, locally sourced ingredients. From tantalizing appetizers to sumptuous main courses and delectable desserts, our talented chefs create culinary masterpieces that will leave you craving for more.</p>
    
            <p>Whether you are celebrating a special occasion, enjoying a romantic dinner, or simply seeking a memorable dining experience, Night Star Restaurant offers the perfect ambiance to create lasting memories. We pride ourselves on creating an atmosphere that exudes elegance and sophistication, making your visit truly unforgettable.</p>
    
         
        </section>
    
        <section>
            <h2>Menu</h2>
            <h3>BREAKFAST</h3>
            <ul>
                <li>Samosa</li>
                <li>Pakora (Vegetable fritters)</li>
                <li>Tandoori Chicken</li>
                <li>Chicken Tikka</li>
                <li>Paneer Tikka</li>
                <li>Aloo Tikki</li>
                <li>Hara Bhara Kabab</li>
                <li>Gobi Manchurian</li>
                <li>Papdi Chaat</li>
                <li>Dahi Vada</li>
            </ul>
            <div class="image-gallery">
                <img src="\RESOURCES\APPETIZER1.jpg" alt="Image 1">
                <img src="\RESOURCES\APPETIZER2.jpg" alt="Image 2">
                <img src="\RESOURCES\APPETIZER3.jpg" alt="Image 3">
            </div>
    
            <h3>Main Courses</h3>
            <ul>
                <li>Butter Chicken</li>
                <li>Chicken Biryani</li>
                <li>Paneer Butter Masala</li>
                <li>Chole Bhature</li>
                <li>Palak Paneer</li>
                <li>Rajma Chawal</li>
                <li>Mutton Curry</li>
                <li>Naan (Plain, Butter, Garlic)</li>
                <li>Tandoori Roti</li>
                <li>Jeera Rice</li>
            </ul>
            <div class="image-gallery">
                <img src="\RESOURCES\MAIN1.jpg" alt="Image 1">
                <img src="\RESOURCES\MAIN2.jpg" alt="Image 2">
                <img src="\RESOURCES\MAIN3.jpg" alt="Image 3">
            </div>
    
            <h3>Desserts</h3>
            <ul>
                <li>Gulab Jamun</li>
                <li>Kheer (Rice Pudding)</li>
                <li>Jalebi</li>
                <li>Rasmalai</li>
                <li>Gajar Halwa (Carrot Halwa)</li>
                <li>Rasgulla</li>
                <li>Malpua</li>
                <li>Shahi Tukda</li>
                <li>Kulfi</li>
                <li>Falooda</li>
            </ul>
            <div class="image-gallery">
                <img src="\RESOURCES\DESSERT1.jpg" alt="Image 1">
                <img src="\RESOURCES\DESSERT2.jpg" alt="Image 2">
                <img src="\RESOURCES\DESSERT3.jpg" alt="Image 3">
            </div>
        </section>
    
        <section>
            <div class="contact-info">
                <p>For room and hall bookings:</p>
                <p>Phone: +918580814344</p>
                <p>Email: honeyyy101@gmail.com</p>
                <div class="location-social">
                    <a href="https://www.google.com/maps/contrib/103805375822734580186/place/ChIJJaA6g_rPGjkR2-vbSwAq9UY/@31.3438659,76.2800038,17.25z/data=!4m8!1m7!3m6!1s0x391acffa833aa025:0x46f52a004bdbebdb!2sNight+Star+guest+house+and+Bar+Restaurant!8m2!3d31.3437675!4d76.2806209!16s%2Fg%2F11j31vw0y3?entry=ttu">
                        <img src="\RESOURCES\map.png" alt="Location Icon">
                    </a>
                    <a href="https://www.facebook.com/your-facebook-page-url" target="_blank">
                        <img src="\RESOURCES\facebook.png" alt="Facebook Icon">
                    </a>
                    <a href="https://www.instagram.com/your-instagram-page-url" target="_blank">
                        <img src="\RESOURCES\instagram.png" alt="Instagram Icon">
                    </a>
                </div>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2023 Night Star Restaurant. All rights reserved.</p>
    </footer>
</body>

</html>
