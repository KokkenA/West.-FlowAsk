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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Feedback - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Give Us Your Feedback</h1>
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
        <form id="feedbackForm">
            <label for="name">Name:</label><br>
            <input type="text" id="name" required><br><br>

            <label for="email">Email:</label><br>
            <input type="email" id="email" required><br><br>

            <label for="feedback">Your Feedback:</label><br>
            <textarea id="feedback" rows="5" required></textarea><br><br>

            <button type="button" onclick="submitFeedback()">Submit</button>
        </form>
        <div id="feedbackMessage" style="display: none;">
            <p>Thank you for your feedback!</p>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>
    <script>
        function submitFeedback() {
            const name = document.getElementById('name').value;
            const email = document.getElementById('email').value;
            const feedback = document.getElementById('feedback').value;

            const feedbackData = JSON.parse(localStorage.getItem('feedbackData')) || [];
            feedbackData.push({ name, email, feedback });
            localStorage.setItem('feedbackData', JSON.stringify(feedbackData));

            document.getElementById('feedbackForm').style.display = 'none';
            document.getElementById('feedbackMessage').style.display = 'block';
        }
    </script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Order - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Order Your Food</h1>
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Employee Area - West-FlowAsk</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Employee Dashboard</h1>
    </header>
    <main>
        <h2>Access Restricted</h2>
        <form id="loginForm">
            <label for="username">Username:</label><br>
            <input type="text" id="username" name="username" required><br><br>

            <label for="password">Password:</label><br>
            <input type="password" id="password" name="password" required><br><br>

            <button type="button" onclick="login()">Login</button>
        </form>

        <div id="employeeContent" style="display: none;">
            <h2>Welcome, Employee!</h2>
            <p>Edit the menu items and prices below:</p>

            <form id="menuForm">
                <div id="menuEditor"></div>
                <button type="button" onclick="addMenuItem()">Add New Item</button>
                <button type="button" onclick="saveMenu()">Save Menu</button>
            </form>
        </div>
    </main>
    <footer>
        <p>&copy; 2024 West-FlowAsk. All rights reserved.</p>
    </footer>

    <script>
        // Dummy login function
        function login() {
            const username = document.getElementById('username').value;
            const password = document.getElementById('password').value;

            if (username === 'employee' && password === 'westflow') {
                document.getElementById('loginForm').style.display = 'none';
                document.getElementById('employeeContent').style.display = 'block';
                loadMenu();
            } else {
                alert('Invalid credentials! Please try again.');
            }
        }

        // Load menu from LocalStorage
        function loadMenu() {
            const menuEditor = document.getElementById('menuEditor');
            const savedMenu = JSON.parse(localStorage.getItem('menu')) || [
                { name: 'Service 1', price: 50 },
                { name: 'Service 2', price: 75 },
                { name: 'Service 3', price: 100 }
            ];

            menuEditor.innerHTML = '';
            savedMenu.forEach((item, index) => {
                const div = document.createElement('div');
                div.innerHTML = `
                    <label>
                        Item Name: <input type="text" value="${item.name}" data-index="${index}" class="menu-item-name">
                    </label>
                    <label>
                        Price: <input type="number" value="${item.price}" data-index="${index}" class="menu-item-price">
                    </label>
                    <button type="button" onclick="deleteMenuItem(${index})">Delete</button>
                    <br><br>
                `;
                menuEditor.appendChild(div);
            });
        }

        // Save menu to LocalStorage
        function saveMenu() {
            const names = document.querySelectorAll('.menu-item-name');
            const prices = document.querySelectorAll('.menu-item-price');

            const menu = Array.from(names).map((nameInput, index) => ({
                name: nameInput.value,
                price: parseFloat(prices[index].value)
            }));

            localStorage.setItem('menu', JSON.stringify(menu));
            alert('Menu saved successfully!');
        }

        // Add new menu item
        function addMenuItem() {
            const menuEditor = document.getElementById('menuEditor');
            const index = menuEditor.childElementCount;
            const div = document.createElement('div');
            div.innerHTML = `
                <label>
                    Item Name: <input type="text" value="New Item" data-index="${index}" class="menu-item-name">
                </label>
                <label>
                    Price: <input type="number" value="0" data-index="${index}" class="menu-item-price">
                </label>
                <button type="button" onclick="deleteMenuItem(${index})">Delete</button>
                <br><br>
            `;
            menuEditor.appendChild(div);
        }

        // Delete a menu item
        function deleteMenuItem(index) {
            const menuEditor = document.getElementById('menuEditor');
            const children = menuEditor.children;
            if (children[index]) {
                menuEditor.removeChild(children[index]);
                loadMenu(); // Reload to fix indexing
            }
        }
    </script>
</body>
</html>
