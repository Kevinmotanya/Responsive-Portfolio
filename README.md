# Responsive-Portfolio
I have basic information about myself and photos for my portfolio
About
Contact
Portfolio that has my pictures and snapshots of my work/projects

Do this to index file
<!-- CSS Stylesheets with Relative Paths -->

<!DOCTYPE html>
<html lang="en-us">

<head>
    <!--This line links my html indexfile with the css styling file-->
    <link rel="stylesheet" href="reset.css">

    <!-- We link our html to the Bootstrap CDN -->
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.1.3/css/bootstrap.min.css" integrity="sha384-MCw98/SFnGE8fJT3GXwEOngsV7Zt27NXFoaoApmYm81iuXoPkFOJwJ8ERdknLPMO" crossorigin="anonymous">
    <!-- We link our html to our local CSS file -->
    <link rel="stylesheet" type="text/css" href="assets/css/style.css">

    <!--Viewport tag-->
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta charset="UTF-8">
    <title>CSS Stylesheets with Relative Paths</title>
</head>

<body>

    <div class="container">

        <!--These are links to other pages-->
        <div id="nav-section">
            <header>
                <h1>Kevin Motanya</h1>
            </header>
            <div class="container">

                <div class="topnav">
                    <a href="index.html">About</a>

                    <a href="portfolio.html">Portfolio</a>

                    <a href="contact.html">Contact</a>

                </div>
            </div>
            <br>
            <!--This line is for About me-->
            <h2>About Me</h2>

            <br>
            <!-- a Bootstrap row with columns -->
            <div class="row">

                <!-- this takes up 1 of thirds width (4/12) -->
                <div class="col-sm-4">
                    <img class="img thumbnail center-block" src="assets/images/bio-image.jpg" alt="bio-image">

                    <p>My name is Kevin Motanya. I originally come from Kenya at the coastal city of Mombasa. I live in the city of New Brighton. I have a bachelors degree in Information Technology and a certificate in call center operations. I have worked as a computer repair tech, an ISP servce agent and done a little more projects that are IT and non-IT related.Being an all-rounded person is my ultimate goal.</p>

                </div>
                <!-- this takes up 1 of thirds width (4/12) -->
                <div class="col-sm-4">
                    <p> I speak the following languages;
                        <p>English </p>
                        <p>Swahili </p>
                        <p>French </p>
                        I'm on the following
                        <p>social media platforms;</p>
                    </p>
                    <P>Facebook (Kevin Agata)</P>
                    <P>Instagram (Kevin Agata)</P>
                    <P>Snapchat (Kevin Swahili)</P>
                    <p>My hobbies are; traveling, Swimming, photography and embracing various cultures.</p>

                </div>
                <!-- this takes up 1 of thirds width (4/12) -->
                <div class="col-sm-4">
                    <img class="img thumbnail center-block" src="assets/images/bio-image6.jpg" alt="Selfie" width="50%">
                    <p> My family size is five siblings and I am third.I see myself in the future as an IT consultant after getting much experience in this field and interacting with more people. After this boot camp I believe that I will not only learn how to code but how to translate our daily life activities into computer perspectives. For more information about me, kindly follow this link <a href="http://www.lipsum.com/">www.lipsum.com</a>.</p>
                </div>

            </div>
        </div>

    </div>
    </div>
    <br>
    <br>
    <br>

    <h3></h3>
    <!-- this is the footer-->
    <footer>&copy; Copyright</footer>
</body>

</html>
