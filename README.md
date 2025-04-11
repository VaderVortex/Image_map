# Ex 04 : Places Around Me
# Date:
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <title>Welcome to My Home</title>
        <style>
            body {
                background-color: #000;
                color: #fff;
                font-family: Arial, sans-serif;
                margin: 0;
                padding: 20px;
            }
            .container {
                max-width: 1000px;
                margin: 0 auto;
                padding: 20px;
                background-color: #111;
                border-radius: 10px;
                box-shadow: 0 0 20px rgba(255,255,255,0.1);
            }
            h1 {
                text-align: center;
                margin-bottom: 40px;
                color: #ffcc00;
                font-size: 2.5em;
                text-transform: uppercase;
            }
            .spot {
                margin-bottom: 50px;
                padding: 20px;
                background-color: #1a1a1a;
                border-radius: 10px;
                transition: transform 0.3s ease;
            }
            .spot:hover {
                transform: translateY(-5px);
            }
            .spot img {
                width: 100%;
                height: 400px;
                object-fit: cover;
                border-radius: 10px;
                border: 2px solid #ffcc00;
            }
            .spot h2 {
                margin: 20px 0 15px;
                color: #ffcc00;
                font-size: 1.8em;
            }
            .spot p {
                line-height: 1.7;
                font-size: 1.1em;
                text-align: justify;
                margin: 0 15px;
                padding-bottom: 10px;
            }
        </style>
    </head>
    <body>
    <div class="container">
        <h1>WELCOME</h1>
        
        <div class="spot">
            <img src="images/map.png" alt="My Home Location">
        </div>
    
        <div class="spot">
            <img src="images/eco_park.jpg" alt="Chetpet Eco Park">
            <h2>Chetpet Eco Park</h2>
            <p>A peaceful escape in the middle of the chaos. This park has a lake where you can go boating, walk peacefully under the trees, or just vibe by the water like you're in a movie montage. The perfect blend of nature and urban design, it's where Chennai's heartbeat slows down to a relaxing rhythm.</p>
        </div>
    
        <div class="spot">
            <img src="images/museum.png" alt="Egmore Museum">
            <h2>Egmore Museum</h2>
            <p>Ancient vibes only. One of the oldest museums in India, this place is filled with sculptures, weapons, and relics from kingdoms that would make even Game of Thrones look mid. Walk through centuries of history in air-conditioned comfort, with artifacts that whisper stories of Tamil Nadu's glorious past.</p>
        </div>
    
        <div class="spot">
            <img src="images/saravana_stores.jpg" alt="Saravana Stores">
            <h2>Saravana Stores</h2>
            <p>The absolute madness of Chennai shopping. It's chaotic, packed, but also iconic. You'll either find a deal of a lifetime or get lost in a maze of sarees and electronic appliances. Pro tip: wear comfortable shoes and keep your bargaining game strong - this is retail therapy on steroids.</p>
        </div>
    
        <div class="spot">
            <img src="images/church.png" alt="CSI Church">
            <h2>CSI Church</h2>
            <p>A calm, sacred place with beautiful gothic architecture. Whether you're there to pray or just admire the stained glass windows, it's all peace and aesthetics inside. The century-old structure stands as a testament to Chennai's colonial heritage, with choir music that'll give you goosebumps.</p>
        </div>
    
        <div class="spot">
            <img src="images/entrance_cafe.jpg" alt="Entrance Cafe">
            <h2>Entrance Cafe</h2>
            <p>This cozy cafe is a hidden gem - perfect for deep convos, chill solo time, or a lowkey date. Great food, better vibes. Try their filter coffee that hits different, and don't miss the mutton samosas that'll make you question all other samosas you've ever had.</p>
        </div>
    </div>
    </body>
    </html>
# OUTPUT
![Screenshot 2025-04-11 211713](https://github.com/user-attachments/assets/b94e3a49-c4b0-452e-bb29-1c16f3e5f2d9)
![Screenshot 2025-04-11 211816](https://github.com/user-attachments/assets/07dc483c-9397-4ae6-9acb-aca422da3d04)
![Screenshot 2025-04-11 211802](https://github.com/user-attachments/assets/642bbe29-63d9-4500-a21c-9e1a09d5ceb1)
![Screenshot 2025-04-11 211752](https://github.com/user-attachments/assets/405fa7b7-5484-4cec-b5eb-333e099d573e)
![Screenshot 2025-04-11 211738](https://github.com/user-attachments/assets/6d9d1c7c-a1c0-4235-83f5-0f691dd96f27)
![Screenshot 2025-04-11 211724](https://github.com/user-attachments/assets/7933401d-98fd-4842-891d-6944cf8f4041)



# RESULT
The program for implementing image maps using HTML is executed successfully.
