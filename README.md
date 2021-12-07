# hallo-github
Hier finden sie, was ich bisher mit HTML und CSS gelernt habe.

<!DOCTYPE html>
<html lang="en">
<head>
    
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Dominos Pizza</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Montserrat:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Open+Sans:ital,wght@0,300;0,400;0,500;0,600;0,700;0,800;1,300;1,400;1,500;1,600;1,700;1,800&display=swap" rel="stylesheet">
    
    <style>

        body{
            font-family: 'open Sans', sans-serif;
            background-color: #f3f5f6;
            padding-left: 100px;
            padding-right: 100px;
        }

        .header-image{
            width: 100%;
            height: 600px;
            object-fit: cover;
            display: block;
        }
           
        .headline{
            color: #831D17;
        }    

        .image-container{
            background-color: white;
            padding: 16px;
        }

        .navbar{
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        a {
            color: #831D17;
            text-decoration: none;
            margin-left: 16px;
            font-weight: 700;
        }

        a:hover {
            text-decoration: underline;
            font-weight: bolder;
            color: rgb(185, 49, 49);
        }

        .text-highlight {
            color: #484846;
            font-size: 48px;
        }

        .text-container {
            background-color: #e6e6e6;
            padding: 8px;
            color: #484846;
            font-weight: 600;
        }

        .maps-frame {
            border: 0;
            height: 350px;
            width: 70%;
        }

        .legal-content {
            padding: 8px;
        }

        .legal-text {
            margin-right: 16px;
        }
    </style>

</head>
<body>
        <div class="navbar">
            <h1 class="headline">
            DOMINOS <br> <span class="text-highlight">PEINE</span>
        </h1>

        <div>
            <a href="https://www.dominos.de/speisekarte">Menü</a>
            <a href="https://www.dominos.de/angebote">Angebote</a>
            <a href="https://gutschein.dominos.de/">Gutscheine</a>
            <a href="https://www.dominos.de/karriere">karriere</a>
        </div>
    </div>



    <div class="image-container">
        <img class="header-image" src="header.jpg">

        <div class="text-container">
            Hier gibt es die besten Pizzen in ganz Peine.
        </div>
    </div>
    
    <div>
        <div class="maps-container">
            <iframe class="maps-frame" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2438.5522381952837!2d10.227271315993677!3d52.3241270584787!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x47afff9d523c3ff5%3A0x23527a1c5a6bbf1!2sDomino&#39;s%20Pizza%20Peine!5e0!3m2!1sde!2sde!4v1638909084860!5m2!1sde!2sde" width="600" allowfullscreen="" loading="lazy"></iframe> 

            <div class="text-container">
                
            </div>
        </div>


    </div>

    <div class="legal-content">
        <span class="legal-text">(c) 2021 - Rony company GmbH</span>| <a href="#">Impressum</a> | <a href="#">Datenschutz</a>
    </div>
</body>
</html>
