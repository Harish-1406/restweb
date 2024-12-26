# Ex.07 Restaurant Website
## Date:25.12.2024

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
index.html

<html>
    <head>
        <style>
            body{
                margin: 0;
                border: 0;
                background: white;
            }
            header{
                text-align: center;
                font-size: 10px;
                background-color: wheat ;
            }
            header img{
                width: 125px;
            }
            nav{
                background-color: black;
                text-align: center;
                color: gray;
                padding: 10px;
            }
            .banner{
                background-image: url('https://as1.ftcdn.net/v2/jpg/03/60/57/68/1000_F_360576850_05Q0KW3mPD8b0fN545hteX0nA3sDEHt4.jpg');
                text-align: right;
                background-size: cover;
                background-position: center;
                color: white;
                padding: 50px;
                }
                .ok{
                    display: flex;
                    justify-content: space-around;
                    padding: 20px;
                    gap: 10px;
                }
                .front{ 
                    background-color: wheat;
                    padding: 15px;
                    border-radius: 10px;
                    text-align: center;
                    width: 30%;
                }   
                .front img{
                    width: 100%;
                    height: 500px;
                }
                footer{
                    background-color: black;
                    color: white;
                    text-align: center;
                    padding: 10px;
                }
        </style>
    </head>
    <body>
        <header class="logo">
        <img src="logo.png">
        <h1>AB's - Absolute Barbecue</h1>
        </header>
        <nav nav navbar-default>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>
        <div class="banner"> 
        <h2>40% Offer This Weekend</h2>
        <p>Don't miss out on our special offer! Visit us this weekend and enjoy delicious meals at discounted prices.</p></div>
        <div class="ok">
            <div class="front">
            <img src="Tandoori Chicken - Happy Muncher.jpeg">
            <h1 style="text-align: center;">
                Our New Menu
            </h1>
            <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Ipsa modi dolores mollitia enim ipsum asperiores tempore dolorum repellendus! Asperiores necessitatibus pariatur deleniti consequuntur eos nisi atque officiis ab voluptate fuga!</p><br>
            <a href="#">See our Menu</a>
            </div>
            <div class="front">
                <img src="Book ur Table.jpg">
                <h2 style="text-align: center;">Reserve Your Table<h2>
                <p>Lorem ipsum, dolor sit amet consectetur adipisicing elit. Dolores facilis atque vel, illo, ipsa debitis temporibus velit animi consequatur autem quas asperiores fugiat nulla, culpa error enim? Est, molestias deleniti.</p><br>
                <a href="book.html">Book Ur Table</a>
            </div>
            <div class="front">
                <img src="opening hours.jpg">
                <h3>Opening Hours</h3>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quisquam nobis ex molestiae fugit voluptas qui voluptatem a nulla omnis maiores!</p>
                <p>Monday to Saturday : 10.am-11.pm<br>
                Sunday : 12pm-11pm</p>
            </div>
        </div>
        <footer>
            <p>&copy;2024 Absolute Barbeque Pvt Ltd. All Rights Reserved.</p>
        </footer>
    </body>
</html>

menu.html

<html>
    <head>
        <style>
            body{
                margin: 0;
                border: 0;
                background: white;
            }
            header{
                text-align: center;
                font-size: 10px;
                background-color: wheat ;
            }
            header img{
                width: 125px;
            }
            nav{
                background-color: black;
                text-align: center;
                color: gray;
                padding: 10px;
            }
            .section{
                background-size: cover;
                margin: 15px;
                display: flex;
                justify-content: space-around;
            }
            .section img{
                width: 150px;
                height: 150px;
            }
            .menus{
                text-align: center;
                padding: 10px;
                border-radius: 10px;
                background-color: wheat;
                margin: 40px;
            }
            footer{
                    background-color: black;
                    color: white;
                    text-align: center;
                    padding: 10px;
                }
        </style>
    </head>
<body>
    <header class="logo">
    <img src="logo.png">
    <h1>AB's - Absolute Barbecue</h1>
    </header>
    <nav nav navbar-default>
        <a href="home.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="section">
        <div class="menus">
        <img src="menu-1.jpg" alt="menu 1">
        <h1>Air Fryer Whole Tandoori</h1>
        <p>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Temporibus, velit.</p>
        <strong>Rs.250</strong>
        </div>
        <div class="menus">
        <img src="menu-2.jpg" alt="menu 2">
        <h1>Butter Chicken Tandoori Pizza</h1>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Omnis, voluptas.
        </p>
        <strong>Rs.200</strong>
        </div>
        <div class="menus">
        <img src="menu-3.jpg" alt="menu 3">
        <h1>Oven Roasted Pork</h1>
        <p>
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Doloribus, aliquam?
        </p>
        <strong>Rs.100</strong>
        </div>
        <div class="menus">
        <img src="menu-4.jpg" alt="menu 4">
        <h1>BBQ Chicken Wings</h1>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Minus enim, odio laboriosam fugit ipsam temporibus?
        </p>
        <strong>Rs.150</strong>
        </div>
    </div>
    <footer>
        <p>&copy;2024 Absolute Barbeque Pvt Ltd. All Rights Reserved.</p>
    </footer>
</body>


book.html

<html>
    <head>
        <style>
            body{
                margin: 0;
                border: 0;
                background: white;
            }
            header{
                text-align: center;
                font-size: 10px;
                background-color: wheat ;
            }
            header img{
                width: 125px;
            }
            nav{
                background-color: black;
                text-align: center;
                color: gray;
                padding: 10px;
            }
            .booking-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .booking-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .booking-form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .booking-form input, .booking-form select, .booking-form button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid gray;
            border-radius: 5px;
        }
        .booking-form button {
            background-color: darkslateblue;
            color: white;
            cursor: pointer;
        }
        .booking-form button:hover {
            background-color: slateblue;
        }
        footer{
                    background-color: black;
                    color: white;
                    text-align: center;
                    padding: 10px;
                }
        </style>
    </head>
    <body>
        <header class="logo">
        <img src="logo.png">
        <h1>AB's - Absolute Barbecue</h1>
        </header>
        <nav nav navbar-default>
            <a href="index.html">Home</a>
            <a href="menu.html">Menu</a>
            <a href="admin.html">Administration</a>
            <a href="contact.html">Contact Us</a>
        </nav>
        <div class="booking-section">
            <h2>Reserve Your Table Now</h2>
            <form class="booking-form">
                <input type="text" name="name" placeholder="Your Full Name" required>
                <input type="email" name="email" placeholder="Your Email" required>
                <input type="tel" name="phone" placeholder="Your Phone Number" required>
                <select name="guests" required>
                    <option value="" disabled selected>Number of Guests</option>
                    <option value="1">1 Guest</option>
                    <option value="2">2 Guests</option>
                    <option value="3">3 Guests</option>
                    <option value="4">4 Guests</option>
                    <option value="5">5 Guests</option>
                    <option value="6+">6+ Guests</option>
                </select>
                <input type="date" name="date" required>
                <input type="time" name="time" required>
                <button type="submit">Book Now</button>
            </form>
            <footer>
                <p>&copy;2024 Absolute Barbeque Pvt Ltd. All Rights Reserved.</p>
            </footer>
        </body>
        </html>


admin.html

<html>
    <head>
        <style>
            body{
                margin: 0;
                border: 0;
                background: white;
            }
            header{
                text-align: center;
                font-size: 10px;
                background-color: wheat ;
            }
            header img{
                width: 125px;
            }
            nav{
                background-color: black;
                text-align: center;
                color: rgba(128, 128, 128, 0.911);
                padding: 10px;
            }
            .admin-container {
                display: grid;
                grid-template-columns: repeat(3, 1fr);
                gap: 30px;
                padding: 50px;
            }
            .admin-member {
                background-color: #fff;
                padding: 20px;
                text-align: center;
                border-radius: 10px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            }
            .admin-member img {
                width: 150px;
                height: 150px;
                border-radius: 50%;
                object-fit: cover;
                margin-bottom: 20px;
            }
            .admin-member {
                background-color: #fff;
                padding: 20px;
                text-align: center;
                border-radius: 10px;
                box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
                border: 3px solid #f1c40f;  /* Adding a yellow border */
            }
            .admin-member h3 {
                font-family: 'Poppins', sans-serif;
                color: #2c3e50;
                margin-bottom: 10px;
            }
            .admin-member p {
                font-size: 1.1em;
                color: #7f8c8d;
            }
            footer{
                    background-color: black;
                    color: white;
                    text-align: center;
                    padding: 10px;
                }
        </style>
    </head>
<body>
    <header class="logo">
    <img src="logo.png">
    <h1>AB's - Absolute Barbecue</h1>
    </header>
    <nav nav navbar-default>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <main>
        <section class="menu-section">
            <h2 style="text-align: center; background-color: black; color: white; padding: 20px;">Administration Team</h2>
            <div class="admin-container">
                <div class="admin-member">
                    <img src="download.jpeg" alt="Person 1">
                    <h3>Harish</h3>
                    <p>CEO & Founder</p>
                </div>
               
                <div class="admin-member">
                    <img src="Ass.jpeg" alt="Person 2">
                    <h3>Samuel Green
                    </h3>
                    <p>Assistant Manager</p>
                </div>
                
                <div class="admin-member">
                    <img src="finan.jpeg" alt="Person 3">
                    <h3>Josh</h3>
                    <p>Financial Manager</p>
                </div>
                
                <div class="admin-member">
                    <img src="damu.webp" alt="Person 4">
                    <h3>Damu</h3>
                </div>
               
                <div class="admin-member">
                    <img src="bhat.webp" alt="Person 5">
                    <h3>Vekatesh Bhat</h3>
                    <p>Executive Chef</p>
                </div>
                
                <div class="admin-member">
                    <img src="rang.jpeg" alt="Person 6">
                    <h3>Rangaraj</h3>
                    <p>Associate Chef</p>
                </div>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy;2024 Absolute Barbeque Pvt Ltd. All Rights Reserved.</p>
    </footer>
</body>
</html>


contact.html

<html>
    <head>
        <style>
            body{
                margin: 0;
                border: 0;
                background: white;
            }
            header{
                text-align: center;
                font-size: 10px;
                background-color: wheat ;
            }
            header img{
                width: 125px;
            }
            nav{
                background-color: black;
                text-align: center;
                color: gray;
                padding: 10px;
            }
            .contact{
                text-align: center;
                padding: 50px;
                }
            .contact strong{
                color: rgb(17, 17, 53);
                
            } 
            footer{
                background-color: black;
                color: white;
                text-align: center;
                padding: 10px;
                }
        </style>
    </head>
<body>
    <header class="logo">
    <img src="logo.png">
    <h1>AB's - Absolute Barbecue</h1>
    </header>
    <nav nav navbar-default>
        <a href="index.html">Home</a>
        <a href="menu.html">Menu</a>
        <a href="admin.html">Administration</a>
        <a href="contact.html">Contact Us</a>
    </nav>
    <div class="contact">
        <h1>Get In Touch with AB's - Absolute Barbecue</h1>
        <p>
            Lorem ipsum dolor sit amet consectetur adipisicing elit. Accusantium labore esse, et consequatur, molestias recusandae harum animi veniam vitae beatae placeat eum ea unde! Et dolore molestias deleniti ex cum, sit, hic autem officiis qui a asperiores recusandae modi eligendi quam saepe vel optio beatae? Sapiente, necessitatibus ipsam expedita veniam facilis nostrum voluptate mollitia fugit eos alias suscipit delectus. Laborum!
        </p>
        <br>
        <strong>Phone: </strong>+91 7010275024 <br>
        <strong>Email: </strong>absouluteBBQ@gamail.com <br>
        <strong>Address: </strong>56, Tharamani Rd, New Colony Opposite to TCS Building Chennai, Tamil Nadu - 600042
    </div>
    <footer>
        <p>&copy;2024 Absolute Barbeque Pvt Ltd. All Rights Reserved.</p>
    </footer>
</body

```

## OUTPUT:
![alt text](<harish/rest/static/Screenshot 2024-12-26 234709.png>)
![alt text](<harish/rest/static/Screenshot 2024-12-26 234735.png>)
![alt text](<harish/rest/static/Screenshot 2024-12-26 234851.png>)
![alt text](<harish/rest/static/Screenshot 2024-12-26 235015.png>)
![alt text](<harish/rest/static/Screenshot 2024-12-26 235031.png>)
![alt text](<harish/rest/static/Screenshot 2024-12-26 235047.png>)


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
