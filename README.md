<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Welcome to West-FlowAsk</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="promotion.html">Promotions</a></li>
                <li><a href="feedback.html">Feedback</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="employee.html">Employee</a></li>
                <li><a href="admin.html">Admin</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Experience Excellence</h2>
        <p>At West-FlowAsk, we combine quality and style to deliver exceptional service.</p>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Us - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>About Us</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="promotion.html">Promotions</a></li>
                <li><a href="feedback.html">Feedback</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="employee.html">Employee</a></li>
                <li><a href="admin.html">Admin</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Location</h2>
        <p>We are located at the heart of the city. Come and visit us!</p>
        <div id="map" style="height: 400px; width: 100%;"></div>
        <script>
            function initMap() {
                var location = { lat: 40.7128, lng: -74.0060 };  // New York coordinates
                var map = new google.maps.Map(document.getElementById("map"), {
                    zoom: 14,
                    center: location
                });
                var marker = new google.maps.Marker({
                    position: location,
                    map: map
                });
            }
        </script>
        <script async src="https://maps.googleapis.com/maps/api/js?key=YOUR_GOOGLE_MAPS_API_KEY&callback=initMap"></script>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Menu - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Menu</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="promotion.html">Promotions</a></li>
                <li><a href="feedback.html">Feedback</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="employee.html">Employee</a></li>
                <li><a href="admin.html">Admin</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Delicious Menu</h2>
        <ul>
            <li>Dish 1 - $10</li>
            <li>Dish 2 - $12</li>
            <li>Dish 3 - $15</li>
            <li>Dish 4 - $20</li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gallery - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Gallery</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="promotion.html">Promotions</a></li>
                <li><a href="feedback.html">Feedback</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="employee.html">Employee</a></li>
                <li><a href="admin.html">Admin</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Our Beautiful Place</h2>
        <img src="images/gallery1.jpg" alt="Gallery Image 1">
        <img src="images/gallery2.jpg" alt="Gallery Image 2">
        <img src="images/gallery3.jpg" alt="Gallery Image 3">
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Promotions - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Special Promotions</h1>
        <nav>
            <ul>
                <li><a href="index.html">Home</a></li>
                <li><a href="menu.html">Menu</a></li>
                <li><a href="gallery.html">Gallery</a></li>
                <li><a href="promotion.html">Promotions</a></li>
                <li><a href="feedback.html">Feedback</a></li>
                <li><a href="order.html">Order</a></li>
                <li><a href="employee.html">Employee</a></li>
                <li><a href="admin.html">Admin</a></li>
            </ul>
        </nav>
    </header>
    <main>
        <h2>Current Offers</h2>
        <p>Check out our amazing deals:</p>
        <ul>
            <li><strong>50% off Service 1</strong> - Valid through November 30.</li>
            <li><strong>Buy One Get One Free</strong> on all products this week!</li>
        </ul>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
</body>
</html>
