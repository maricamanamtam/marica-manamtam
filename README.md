<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Webpage with PNG Banner</title>
    <!-- Google Font Link -->
    <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
    <style>
        /* Style for the top banner */
        .banner {
            position: relative;
            width: 100%;
            height: 746px;
            background-image: url('https://i.imgur.com/KoClbJC.jpeg');
            background-size: cover;
            background-position: top center;
            background-repeat: no-repeat;
        }

        /* Style for the banner text */
        .banner-text {
            position: absolute;
            top: 170px;
            right: 200px;
            color: white;
            font-size: 33px;
            font-weight: bold;
            font-family: 'Roboto', sans-serif; /* Applying the Google font */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        /* Style for the content text (Just below the banner text) */
        .content-text {
            position: absolute;
            top: 280px;
            right: 187px;
            color: white;
            font-size: 25px;
            font-weight: normal;
            font-family: 'Roboto', sans-serif; /* Applying the Google font */
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            width: 50%;
            line-height: 1.5;
        }

        /* Style for the image on the left side */
        .banner-image-left {
            position: absolute; /* Position relative to the banner */
            top: 105px; /* Adjust the distance from the top */
            left: 200px; /* Adjust the distance from the left */
            width: 450px; /* Set the width of the image */
            height: auto; /* Keep the aspect ratio */
        }

        body {
            font-family: 'Roboto', sans-serif;
            margin: 0;
            padding: 0;
        }

        .content {
            padding: 20px;
        }
    </style>
</head>
<body>
    <!-- Banner Section with text on top -->
    <div class="banner">
        <!-- Image on the left side -->
        <img src="https://i.imgur.com/61Lwuvc.jpeg" class="banner-image-left">
        
        <div class="banner-text">
            <h1>Marica Franzeska O. Manamtam</h1>
        </div>
        
        <!-- Content text directly below the banner text -->
        <div class="content-text">
            <p>I am a motivated and tech-savvy professional with a strong attention 
            to detail and a commitment to delivering high-quality work. As a 
            fast learner, I can quickly adapt to new tools and technologies, 
            and I am always eager to take on new challenges. I am open to feedback 
            and willing to continue training to improve my skills. My work ethic, 
            professionalism, and ability to collaborate with teams make me valuable 
            to any organization.</p>
        </div>
    </div>

    <!-- Page Content Below the Banner -->
    <div class="content">
        <p>Some content here...</p>
    </div>
</body>
</html>
