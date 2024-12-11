# Ex.07 Restaurant Website
## Date:11.12.24

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
main.html

<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start;
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px;
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;          
            width: 300;
            height: 550px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 40px;
            padding: 1px;
            position: absolute;
            top:220
        }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.png" alt="Restaurant Logo">
            <h2 class="logo">Liha Otnas</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
        </div>
        <p class="start">Our Team</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Arjun Kapoor</h2>
                <p>(Executive Chef)<br></p>
                <img src="images.jpeg" class="i">
                
                <p><br>A culinary maestro, the Executive Chef is the creative genius 
                    behind the menu. With years of experience in world-class kitchens,
                     they craft dishes that tantalize the taste buds and delight the soul.
                      Their dedication to quality ingredients and presentation ensures
                       every plate reflects the restaurant's premium standards.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Ahil Santo</h2>
                <p>(Restaurant Manager)<br></p>
                <img src="aahilsanto.jpg" class="i1">
                
                <p><br>As the driving force behind this premium restaurant, Santo ensures
                     the finest dining experience for guests. </p>
                
            </div>
            <div class="box2"> 
                
                <h2>Ravi Desai</h2>
                <p>(Head Waiter)<br></p>
                <img src="Captain-Waiter.jpg" class="i">
                
                <p><br>The Head Waiter exemplifies service excellence, ensuring every 
                    guest enjoys a seamless and memorable dining experience. With a 
                    deep understanding of hospitality, they lead the service staff, 
                    manage table arrangements, and cater to the individual preferences 
                    of each guest, embodying the warmth of the 
                    restaurant.</p>
                
            </div>
            
            
        </div>
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Anjali Nair</h2>
                <p>(Restaurant Supervisor)<br></p>
                <img src="manager.jpeg" class="i">
                
                <p><br>The Restaurant Supervisor is the backbone of daily operations,
                     ensuring the highest standards of service and ambiance. From
                      coordinating staff schedules to maintaining a welcoming environment,
                       they ensure every detail is perfect, reflecting the restaurant's
                        premium reputation.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Sneha Reddy</h2>
                <p>(HR Manager)<br></p>
                <img src="hr.jpg" class="i">
                
                <p><br>The HR Manager is the people champion, ensuring the team thrives 
                    in a supportive and inspiring environment. They oversee recruitment,
                     training, and staff well-being, cultivating a team that upholds the
                      restaurant's commitment to luxury and excellence.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Priya Mehta</h2>
                <p>(Sous Chef)<br></p>
                <img src="Sous-Chef-job-description_5719402.avif" class="i">
                
                <p><br>Second-in-command in the kitchen, the Sous Chef plays a vital role
                     in maintaining the restaurant's culinary excellence. They assist in
                      menu development, oversee daily food preparation, and ensure the
                       kitchen runs smoothly, making every dining experience exceptional.

                </p>
                
            </div>
       
        
        
    </div>
</body>
</html>


admin.html

<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start;
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px;
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255); 
            padding: 10px;          
            width: 300;
            height: 550px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 40px;
            padding: 1px;
            position: absolute;
            top:220
        }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.png" alt="Restaurant Logo">
            <h2 class="logo">Liha Otnas</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
        </div>
        <p class="start">Our Team</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Arjun Kapoor</h2>
                <p>(Executive Chef)<br></p>
                <img src="images.jpeg" class="i">
                
                <p><br>A culinary maestro, the Executive Chef is the creative genius 
                    behind the menu. With years of experience in world-class kitchens,
                     they craft dishes that tantalize the taste buds and delight the soul.
                      Their dedication to quality ingredients and presentation ensures
                       every plate reflects the restaurant's premium standards.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Ahil Santo</h2>
                <p>(Restaurant Manager)<br></p>
                <img src="aahilsanto.jpg" class="i1">
                
                <p><br>As the driving force behind this premium restaurant, Santo ensures
                     the finest dining experience for guests. </p>
                
            </div>
            <div class="box2"> 
                
                <h2>Ravi Desai</h2>
                <p>(Head Waiter)<br></p>
                <img src="Captain-Waiter.jpg" class="i">
                
                <p><br>The Head Waiter exemplifies service excellence, ensuring every 
                    guest enjoys a seamless and memorable dining experience. With a 
                    deep understanding of hospitality, they lead the service staff, 
                    manage table arrangements, and cater to the individual preferences 
                    of each guest, embodying the warmth of the 
                    restaurant.</p>
                
            </div>
            
            
        </div>
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Anjali Nair</h2>
                <p>(Restaurant Supervisor)<br></p>
                <img src="manager.jpeg" class="i">
                
                <p><br>The Restaurant Supervisor is the backbone of daily operations,
                     ensuring the highest standards of service and ambiance. From
                      coordinating staff schedules to maintaining a welcoming environment,
                       they ensure every detail is perfect, reflecting the restaurant's
                        premium reputation.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Sneha Reddy</h2>
                <p>(HR Manager)<br></p>
                <img src="hr.jpg" class="i">
                
                <p><br>The HR Manager is the people champion, ensuring the team thrives 
                    in a supportive and inspiring environment. They oversee recruitment,
                     training, and staff well-being, cultivating a team that upholds the
                      restaurant's commitment to luxury and excellence.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Priya Mehta</h2>
                <p>(Sous Chef)<br></p>
                <img src="Sous-Chef-job-description_5719402.avif" class="i">
                
                <p><br>Second-in-command in the kitchen, the Sous Chef plays a vital role
                     in maintaining the restaurant's culinary excellence. They assist in
                      menu development, oversee daily food preparation, and ensure the
                       kitchen runs smoothly, making every dining experience exceptional.

                </p>
                
            </div>
       
        
        
    </div>
</body>
</html>


menu1.html

<html>
<head>
    <title>Menu</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
            
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
       

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%; 
            
        }

        .image {
            width: 200px; 
            height: auto; 
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem; 
            color: rgba(25, 19, 85, 0.667); 
            text-align: center;
            margin: 10px 0; 
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .box2{
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            color: aliceblue;
            border: 4px solid rgb(255, 255, 255);
            padding: 10px;         
            width: 300;
            height: 360px;  
            border-radius: 20px;         
            text-align: justify;
            background-color: rgba(0, 0, 0, 0.522);
            
            
        }
        .box2 a{
            color: aliceblue;
            
        }
        .lowerbox{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            padding: 5%;
            gap: 40px;
        }
        .i{
            height:200;
            width: 300;
        }
        .lowerbox2{
            display: flex;
            flex-direction: row;
            justify-content: flex-start;
            gap:40px;
        }
        .i1{
            height: 300px;
            width: 300px;
        }
        
        .start{
            color: aliceblue;
            font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            font-size: 40px;
            padding: 1px;
            position: absolute;
            top:220
        }
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.png" alt="Restaurant Logo">
            <h2 class="logo">Liha Otnas</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
        </div>
        <p class="start">Liha Exclusive</p>
        <div class="lowerbox">
            
            <div class="box2"> 
                
                <h2>Royal Butter Chicken</h2>
                
                <img src="food1.avif" class="i">
                
                <p><br> Succulent chicken cooked in creamy tomato sauce with aromatic spices.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Herb-InfusedGrilled Lamb</h2>
               
                <img src="food2.avif" class="i">
                
                <p><br>Tender lamb chops seasoned with Mediterranean herbs.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Seafood Symphony</h2>
               
                <img src="food3.avif" class="i">
                
                <p><br>A medley of shrimp, calamari, and mussels in a tangy sauce.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Golden Prawns</h2>
                
                <img src="food4.webp" class="i">
                
                <p><br>Crispy battered prawns served with a spicy dip.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Stuffed Mushroom Caps</h2>
               
                <img src="food5.webp" class="i">
                
                <p><br>Mushrooms filled with cheese and herbs, baked to perfection.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Tandoori Paneer Tikka</h2>
                
                <img src="food6.jpeg" class="i">
                
                <p><br>Marinated cottage cheese cubes grilled over charcoal.</p>
                
            </div>
            
            
        </div>
        <div class="lowerbox2">
            <div class="box2"> 
                
                <h2>Exotic Veggie Platter</h2>
                
                <img src="food7.jpeg" class="i">
                
                <p><br>Assorted seasonal vegetables in flavorful gravies.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Spicy Pepper Beef</h2>
               
                <img src="food8.jpg" class="i">
                
                <p><br>Wok-tossed beef slices in a fiery black pepper sauce.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Signature Biryani </h2>
                
                <img src="food9.jpeg" class="i">
                
                <p><br>Fragrant basmati rice layered with spiced meat or vegetables.

                </p>

                
            </div>
            <div class="box2"> 
                
                <h2>Saffron Gulab Jamun</h2>
            
                <img src="food10.avif" class="i">
                
                <p><br>Soft, golden dumplings soaked in saffron syrup</p>
                
            </div>
            <div class="box2"> 
                
                <h2>Dark Chocolate Lava Cake</h2>
                
                <img src="food11.jpeg" class="i">
                
                <p><br> Warm, gooey chocolate cake served with vanilla ice cream.</p>
                
            </div>
            <div class="box2"> 
                
                <h2>ALiha's Secret Mocktail</h2>
             
                <img src="food12.webp" class="i">
                
                <p><br>A refreshing blend of exotic fruits and herbs.</p>
                
            </div>
       
        
        
    </div>
</body>
</html>


contact.html

<html>
<head>
    <title>My Restaurant</title>
    <style>
        body {
            width: 100%;    
            background-image: url(bg.png);
            background-repeat: no-repeat;
            background-size: cover;
            background-position: center;
            margin:0; 
            overflow-y: scroll;
        }
        .top{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgb(224, 224, 152);
            width: 100%;
            
        }
        .bottom{
            align-items: center;
            display: flex;
            justify-content: flex-start;
            flex-direction: column;
            background-color: rgba(216, 216, 197, 0.928);
            width: 100%;
        }

        .main {
            
            display: flex; 
            flex-direction: column; 
            align-items: center; 
            justify-content: flex-start; 
            position: relative; 
            top: 10px; 
            width: 100%;
        }

        .image {
            width: 200px; 
            height: auto;
        }
        
        .logo {
            font-family: Arial, Helvetica, sans-serif;
            font-size: 2rem;
            color: rgba(25, 19, 85, 0.667);
            text-align: center; 
            margin: 10px 0;
        }
        .hr{
            width: 100%;
        }
        
        .sub{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 11px;
            margin: auto;
            align-items: center;
            
        }
        .root{
            display: flex;
            align-items: center;
            justify-content: center;
            background-color: rgba(0, 0, 0, 0.47);
            height: 500;
            width: 800;
            font-size: 20;
        }
        
        
        
        
    </style>
</head>
<body>
    <div class="main">
        <div class="top">
            <img class="image" src="lo.png" alt="Restaurant Logo">
            <h2 class="logo">Liha Otnas</h2>
            <h3 class="sub">A Premium Restaurant</h3>
            <hr class="hr">
            
        </div>
    
        <br>
        <br>
        <div class="root">
            <font color="white">
            <p>
                Contact Us<br>
                <br>
                Liha Otnas<br>
                <ul><li>Address: 123 Gourmet Street, Culinary Town, Chennai 600001</li>
                    <li>Phone: +91-768-567-345</li>
                    <li>Email: contact@lihaotnas.com</li>
                    <li>Website: www.lihaotnas.com</li>
                </ul>
                
                We are here to assist you with reservations, inquiries, and feedback.<br> Feel 
                free to reach out to us during our business hours, and we'll be delighted to 
                serve you.<br> Your satisfaction is our priority!</p>
            </font>
        </div>
        
        
    </div>
</body>
</html>

```
## OUTPUT:

Main

![alt text](<Screenshot (44).png>)


![alt text](web-ex7main_page-0001.jpg)

Admin

![alt text](<Screenshot (46).png>)


![alt text](web-ex7admini_page-0001.jpg)

Menu

![alt text](<Screenshot (47).png>)


![alt text](web-ex7menu_page-0001.jpg)

Contact Us

![alt text](<Screenshot (48).png>)

## RESULT:

The program for designing software company website using HTML and CSS is completed successfully.
