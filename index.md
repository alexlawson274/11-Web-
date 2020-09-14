<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" href="Resources/assets/styles.css">
</head>

<body>
    <!--NavBar-->
    <!--https://www.w3schools.com/howto/howto_css_dropdown_navbar.asp-->
    <nav>
        <!--Latitude - brings back to the homepage-->
        <div class="navbar">
        <a href="index.html">Home</a>
        <!--Plots dropdown menu with 4 visualisation pages-->
        <div class="dropdown">
            <button class="dropbtn">Plots<i class="fa fa-caret-down"></i>
            </button>
            <div class="dropdown-content">
            <a href="City v Max Temp.html">Temperature </a>
            <a href="City v Cloudiness.html">Cloudiness </a>
            <a href="City v Humidity.html">Humidity </a>
            <a href="City v Windspeed.html">Windspeed</a>
            </div>
        </div>
        <!--Comparison one page with 4 image-->
        <a href="comparison.html">Comparision</a>
        <!--Data - one with table-->
        <a href="Table.html">Table Data</a>
    </div>
</nav>





    <div class = "container-fluid">
        <section class = "row">
            <div class = "form-col-8">
                
                <!--Summary-->
                <section id ="content">
                <h1>Comparative Weather Study</h1>
                
                <img src="Resources/assets/images/Fig1.png">
                <p> This project was intended to analyze how the weather 
                    changes the closer the location is to the equator.
                    In order to conduct this analysis we looked at 500 randomally 
                    selected cities from the OpenWeather API.
                </p>
                <p>After pulling together the dataset, we analysed 4 elements of the
                    weather- Humidity, max temperature, wind speed and cloudiness. The results of
                    these studies are located in this webpage, simply click on the graph to follow
                    the link.</p>
                </section>
            </div>
            <div class = "form-col-4">
<!--Visualisation 4 images h2 header-->
                <h2>Visualizations</h2>
                <div id ="images">
                    <a href="City v Max Temp.html"><img src="Resources/images/Fig1.png" class="figures"></a>
                    <a href="City v Humidity.html"><img src="Resources/images/Fig2.png" class="figures"></a>
                    <a href="City v Cloudiness.html"><img src="Resources/images/Fig3.png" class="figures"></a>
                    <a href="City v Windspeed.html"><img src="Resources/images/Fig4.png" class="figures"></a>
                </div>

            </div>

    

        </section>

    </div>


</body>

