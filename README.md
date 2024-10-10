# Ex04 Places Around Me
## Date: 10-10-2024

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE

## map.html
```
<html>
    <head>
        <title>kanchipuram</title>
        <style>
            h1{
                font-family: Algerian;
                color: rgb(236, 112, 11);
                font-size: large;
                
            }
        </style>
    </head>
    <body>
        <h1 align="center">Kanchipuram - Welcome to the Temple City (Padmavathi M)</h1>
        
        <center>
            <img src="map.png" usemap="#mapnew">
            
            <map name="mapnew">
                <area target="" alt="kanchikamatchi" title="kamatchi" href="kanchikamatchi.html" coords="296,253,596,337" shape="rect">
                <area target="" alt="ekambaranathar" title="ekambaranathar" href="ekam.html" coords="310,210,50" shape="circle">
                <area target="" alt="varadharajar" title="athi varathar" href="athi_caradhar.html" coords="520,487,667,569" shape="rect">
                <area target="" alt="vazhakarutheesvarar" title="vazhakarutheesvarar" href="vazha.html" coords="355,417,39" shape="circle">
                <area target="" alt="sonnavanam seitha perumal" title="sonnavanam seitha perumal" href="sonnavannam.html" coords="341,450,562,503" shape="rect">
                

            
        
            </map> 
        </center> 
    </body>
</html>
```
## kanchikamatchi.html
```
<html>
    <head>
        <title>kanchi kamatchi</title>
    </head>
    <body bgcolor="lavender">
        <h1 align="center">Sri Kanchi Kamatchi Thirukoil</h1>
        <p>Kanchi Kamakshi Temple is the most important Amman/ Devi temples in South India. It is located in the city of Kanchipuram which is 110 kms away from Chennai. It is also known by its former names Kanchiampathi, Kanjeevaram, and the nickname "The City of Thousand Temples". Apart from Kamakshi Amman temple other important temples here are Sri Ekambaranthar Temple, Sri Varadaraja Perumal Temple, Sri Ulagalanda Perumal Temple, Sri Kumarakottam Temple, Sri Kailasanathar Temple, Sri Kachapeswarar Temple etc.

            Here Main deity Kamakshi (divine form of Parvati Devi) is seated in padmasana posture holding sugarcane bow, bunch of flowers in the lower two of her arms and has a pasha (lasso), an ankusha (goad) in her upper two arms with a parrot sitting on the flowers. The Goddess also has a Chandraperai (a shape of moon like structure) on her forehead. Sri Adi Sankaracharya has installed Srichakram before the main deity which holds the power of Sri Kamakshi Devi. The most interesting fact is there is no other Parvati temple in Kanchi, which is very unusual given that in Tamilnadu you can see a temple at every corner of the street. The temple was built in 6th Century AD by Pallava kings.</p>
            <img align="left" src="https://www.pujanpujari.com/wp-content/uploads/2022/04/Kanchi-Kamakshi-Amman-Temple.jpeg" height="450" width="500">
    
            <img align="right" src="https://sanity-admin.rudraksha-ratna.com/static/images/blogs/Kamakshi+mata.jpg" height="450" width="450">
            
    </body>
</html>
```
## ekam.html
```
<html>
    <head>
        <title>Ekkambareeswarar</title>
        <style>
            body{
                background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRhd6yT2TXUgXy3rVLZ1dWO9Wsu5fJFL5xUTA&s');
                background-size: cover;
            }
            p{
                color: rgb(3, 9, 9);
            }
        </style>
    </head>
    <body>
        <h1 align="center" style="color:darkred">காஞ்சிபுரம் ஏகாம்பரநாதர் கோயில்</h1>
        
        <p>இத்தலத்தின் இறைவியான ஏலவார்குழலி அம்மையார், உலகம் உய்யவும், ஆகமவழியின்படி ஈசனை பூசிக்கவும் கயிலையிலிருந்து காஞ்சிபுரத்திற்கு எழுந்தருளினார். அங்கு கம்பையாற்றின் கரையில் திருவருளால் முளைத்து எழுந்த சிவலிங்கத் திருவுருவைக் கண்டு பூசித்தார். அதுபொழுது கம்பை மாநதி பெருக்கெடுத்து வந்தது. அம்மையார் பயந்து பெருமானை இறுகத் தழுவிக்கொண்டார். அப்பொழுது இறைவனது லிங்கத் திருமேனி குழைந்து வளைத்தழும்பும் முலைத் தழும்பும் தோன்றக் காட்சியருளினார். அதுகாரணம்பற்றித் சிவனுக்கு தழுவக் குழைந்தநாதர் என்னும் பெயர் உண்டாயிற்று.</p>
        <br>
        <center><img src="https://www.indiatempletour.com/wp-content/uploads/2019/07/Ekambareswarar.jpg" height="500" width="500"></center>
    </body>
</html>
```
## vazha.html
```
<html>
    <head>
        <title>vazhakarutheeswarar</title>
        <style>
            body{
                background-image: url('https://img.pikbest.com/wp/202343/light-color-texture-background-textured-with-vintage-colors_9989454.jpg!sw800');
                background-size: cover ;
            }  
            p{
                font-size: large;
                font-family:monospace;

            }
            h1{
                color: maroon;
            }
            
        </style>
    </head>
    <body>
        <h1 align="center">Sri Vazhakarutheeswara Koil</h1>
        <p>Sri Vazhakarutheeswarar Temple is an ancient Hindu temple which is dedicated to Lord Shiva. The temple is one of the best places to see in Kanchipuram, Tamil Nadu. The literal meaning of the temple is The God who Solve cases. It is believed that people who have extended cases issues visit here and perform various rituals like puja and Abhishek on every Monday to seek blessings from Lord Siva in the form of Vazhakarutheeswarar(Linga). One should offer puja in this temple continuously for sixteen Mondays so they can get favourable results.

        </p>
        <br>
        <center>
        <img src="https://temple.yatradham.org/public/Product/temple/temple_95jLdtvH_202307111026050.webp" height="500" width="500">
        </center>
    </body>
</html>
```
## sonnavannam.html
```
<html>
    <head>
        <title>Sonnavannam keta perumal</title>
        <style>
            body{
                background-image: url('https://media.istockphoto.com/id/1400918939/vector/summer-sunny-clear-sky-orange-and-blue-abstract-defocused-color-gradient-background-vector.jpg?s=612x612&w=0&k=20&c=H7zCHx8fPia02XttG3pkAVhLRm1VQSWEUi7Tl2agHms=');
                background-size: cover;
            }
            h1{
                color: crimson;
            }
        </style>
    </head>
    <body>
        <h1 align="center">SonnaVannam Seitha Perumal</h1>
        <p>Yathothkari Perumal Temple also known as Sonnavannam Seitha Perumal is one of the oldest Vishnu shrines also Divya Desam located in Kanchipuram. The Lord is enshrined here as Yathothkari, which translates into Tamil as Sonnavannam Seitha Perumal. Goddess Komalavalli serves as his consort.

            The Lord was claimed to have been seen by Goddess Saraswati and Thirumazhisai Azhwar here. The presiding deity is unusual in that he is lying on the snake couch with his head to the left and his feet to the right, as opposed to the customary head-to-the-right and feet-to-the-left orientation.
            
            This Lord has received honour in the devotional compositions of the Azhwar saints, and hence this temple remains a Divya Desam, a particularly revered Vishnu dwelling. This also happens to be the birthplace of the Azhwar saint Poigai Azhwar. In traditional tales, this holy location is also known as Thiruvekka.
        </p>
        <br>
        <center><img src="https://gumlet.vikatan.com/vikatan%2F2019-07%2Fa40cb2ab-35f1-482b-a878-533642e4a6a6%2F152486_thumb.jpg?format=auto" width="500" height="500"></center>

    </body>
</html>
```
## athi_caradhar.html
```
<html>
    <head>
        <title>Athi Varathar</title>
        <style>
            body{
                background-image: url('https://t3.ftcdn.net/jpg/06/27/85/70/360_F_627857017_5r2FsJYJeZfufqiXcUvKCENF3fz4xFyg.jpg');
                background-size: cover;
            }
        </style>
    </head>
    <body>
        <h1 align="center">Varadharaja Perumal Kovil</h1>
        <p>The Deity of Athi Varadar is one among the four Deities of Lord Varadaraja worshiped by Brahma. In the Satya-yuga this Deity was carved out of Fig tree wood by Vishwakarma. This was the mula-vigraha worshiped in the sanctum of the Kanchi Varadaraja Perumal Temple until the early 16th century. Due to the Muslim invasion, the Athi Varadar vigraha was immersed inside the sacred pushkarani of the temple secretively and the truth was known only to one family.

            For forty long years, the temple had no Deity for worship thus no puja happening in the temple. The two brothers in the Dhatacharya lineage under whose authority the Deity was hidden, passed away thus taking away the secret forever. Their two sons tried their best to bring back the Deities to Kanchipuram. One Madhwa devotee brought the utsavar back from the Udayar Palayam forest and utsavar puja began.
        </p>
        <br>
        <center>
            <img src="https://satyaagrah.com/templates/yootheme/cache/f3/athi25Jan-f33b0c6e.jpeg" width="500" height="500">
        </center>

    </body>
</html>
```
## OUTPUT
## map.html
![Screenshot 2024-10-10 100357](https://github.com/user-attachments/assets/6c247685-8496-4cc9-bc7a-3bbe0f80401e)

## kanchikamatchi.html
![Screenshot 2024-10-10 100458](https://github.com/user-attachments/assets/f59de8a6-1a2d-41cc-b7e9-f6b78a697a0d)

## ekam.html
![Screenshot 2024-10-10 100427](https://github.com/user-attachments/assets/672a869c-975c-4bb8-9c13-9d9976c5d3df)

## vazha.html
![Screenshot 2024-10-10 100519](https://github.com/user-attachments/assets/a0ff6c7a-fcbd-414e-b4a4-94d5285de960)

## sonnavannam.html
![Screenshot 2024-10-10 100611](https://github.com/user-attachments/assets/e9a61b68-5659-45c3-a8d2-77782f82101f)

## athi_caradhar.html
![Screenshot 2024-10-10 100627](https://github.com/user-attachments/assets/b402d6e2-0411-4c15-9ec0-800f7888d78c)

## RESULT
The program for implementing image maps using HTML is executed successfully.
