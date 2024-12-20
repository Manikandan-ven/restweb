# Ex.07 Restaurant Website
## Date:

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
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Delicious Bistro</title>
    <link rel="stylesheet" href="./res.css">
</head>

<body>
    <div id="content">
        <header>
            <h1>Welcome to Delicious Bistro</h1>
            <nav>
                <a href="#" onclick="showSection('menu')">Menu</a>
                <a href="#" onclick="showSection('about')">About Us</a>
                <a href="#" onclick="showSection('administration')">Administration</a>
                <a href="#" onclick="showSection('contact')">Contact</a>
            </nav>
        </header>

        <section id="menu">
            <h2>Our Menu</h2><br>
            <div class="container">
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Greek salad</h3>
                        <p>Price: $12</p>
                    </div>
                    <img class="menu-image" src="./food_1.png" alt="Greek Salad">
                </div>

                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Veg Salad</h3>
                        <p>Price: $18</p>
                    </div>
                    <img class="menu-image" src="./food_2.png" alt="Veg Salad">
                </div>

                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Clover Salad</h3>
                        <p>Price: $16</p>
                    </div>
                    <img class="menu-image" src="./food_3.png" alt="Clover Salad">
                </div>

                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Chicken Salad</h3>
                        <p>Price: $24</p>
                    </div>
                    <img class="menu-image" src="./food_4.png" alt="Chicken Salad">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Lasagna Rolls</h3>
                        <p>Price: $14</p>
                    </div>
                    <img class="menu-image" src="./food_5.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Peri Peri Rolls</h3>
                        <p>Price: $12</p>
                    </div>
                    <img class="menu-image" src="./food_6.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Chicken Rolls</h3>
                        <p>Price: $20</p>
                    </div>
                    <img class="menu-image" src="./food_7.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Veg Rolls</h3>
                        <p>Price: $15</p>
                    </div>
                    <img class="menu-image" src="./food_8.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Ripple Ice Cream</h3>
                        <p>Price: $14</p>
                    </div>
                    <img class="menu-image" src="./food_9.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Fruit Ice Cream</h3>
                        <p>Price: $22</p>
                    </div>
                    <img class="menu-image" src="./food_10.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Jar Ice Cream</h3>
                        <p>Price: $10</p>
                    </div>
                    <img class="menu-image" src="./food_11.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Vanilla Ice Cream</h3>
                        <p>Price: $12</p>
                    </div>
                    <img class="menu-image" src="./food_12.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Chicken Sandwich</h3>
                        <p>Price: $12</p>
                    </div>
                    <img class="menu-image" src="./food_13.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Vegan Sandwich</h3>
                        <p>Price: $18</p>
                    </div>
                    <img class="menu-image" src="./food_14.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Grilled Sandwich</h3>
                        <p>Price: $16</p>
                    </div>
                    <img class="menu-image" src="./food_15.png" alt="Lasagna Rolls">
                </div>
                <div class="menu-item">
                    <div class="menu-content">
                        <h3>Bread Sandwich</h3>
                        <p>Price: $24</p>
                    </div>
                    <img class="menu-image" src="./food_16.png" alt="Lasagna Rolls">
                </div>
            </div>
    </div>
    </section>

    <section id="about">
        <div class="about-content">
            <h2 class="about-heading">About Us</h2>
            <p>At Delicious Bistro, we are passionate about creating memorable dining experiences through
                exceptional
                food, outstanding service, and a warm, inviting atmosphere. Our chefs craft each dish using the
                freshest
                ingredients, ensuring every bite is packed with flavor and authenticity. Whether you're joining us
                for a
                casual meal or a special celebration, we are dedicated to making your visit truly delightful. Our
                menu
                blends traditional flavors with modern culinary techniques, offering something for everyone. Come
                and
                savor the experience at Delicious Bistro, where great food and great memories are made.</p>
        </div>

    </section>

    <section id="administration">
        <div class="about-chef">
            <h2 class="chef-heading">Our Chefs</h2>
        </div>
        <div class="chef-card-list">
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_1_ranveer.png" alt="">
                <div class="about-chef-content">
                    <h3>Ranveer Brar</h3>
                    <h3>Chief Cook</h3>
                    <p>Bio: Ranveer Brar is an acclaimed chef known for his innovative cooking and TV shows.</p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_2_vikas.png" alt="">
                <div class="about-chef-content">
                    <h3>Vikas Khanna</h3>
                    <h3>Michelin Star Chef</h3>
                    <p>Bio: Vikas Khanna is an internationally renowned chef, restaurateur, and cookbook author.</p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_3_sanjeev.png" alt="">
                <div class="about-chef-content">
                    <h3>Sanjeev Kapoor</h3>
                    <h3>Culinary Expert</h3>
                    <p>Bio: Sanjeev Kapoor is a famous chef and the host of the popular show "Khana Khazana."</p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_4_tarla.png" alt="">
                <div class="about-chef-content">
                    <h3>Tarla Dalal</h3>
                    <h3>Celebrity Chef</h3>
                    <p>Bio: Tarla Dalal was an iconic cookbook author and television personality in India.</p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_5_manish.png" alt="">
                <div class="about-chef-content">
                    <h3>Manish Mehrotra</h3>
                    <h3>Chef at Indian Accent</h3>
                    <p>Bio: Manish Mehrotra is a renowned chef known for his modern take on traditional Indian cuisine.
                    </p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_6_hemantpng.png" alt="">
                <div class="about-chef-content">
                    <h3>Hemant Oberoi</h3>
                    <h3>Executive Chef</h3>
                    <p>Bio: Hemant Oberoi is an executive chef at Taj Hotels, known for his expertise in world cuisines.
                    </p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="./chef_7_ananda.png" alt="">
                <div class="about-chef-content">
                    <h3>Ananda Solomon</h3>
                    <h3>Executive Chef</h3>
                    <p>Bio: Ananda Solomon is a celebrated chef known for his skills in Asian and Continental cuisine.
                    </p>
                </div>
            </div>
            <div class="about-chef-card">
                <img class="chef-image" src="chef_8_ritu.png" alt="">
                <div class="about-chef-content">
                    <h3>Ritu Dalmia</h3>
                    <h3>Chef and Restaurateur</h3>
                    <p>Bio: Ritu Dalmia is a famous chef and the owner of the restaurant "Diva" in Delhi.</p>
                </div>
            </div>
        </div>
    </section>


    <section id="contact">
        <h2>Contact Us</h2>
        <p>If u have any question or would like to make a reservation,please contact us!</p>
        <p>Email: <a href="mailto:manikandan19@gmail.com">manikandan19@gmail.com</a></p>
        <p>Phone:7200465246</p>
    </section>
    </div>

    <footer>
        <p>&copy; 2024 Delicious Bistro. All rights reserved.</p>
    </footer>

    <script src="./res.js"></script>

</body>
```
## OUTPUT:
![alt text](<Screenshot 2024-12-07 074159-1.png>) 
![alt text](<Screenshot 2024-12-07 074213-1.png>)

![alt text](<Screenshot 2024-12-07 074341-1.png>)

 ![alt text](<Screenshot 2024-12-07 074358-1.png>)

## RESULT:




The program for designing software company website using HTML and CSS is completed successfully.
