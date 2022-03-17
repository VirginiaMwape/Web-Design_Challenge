<!doctype html>
<html lang="en">
<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/css/bootstrap.min.css" integrity="sha384-ggOyR0iXCbMQv3Xipma34MD+dH/1fQ784/j6cY/iJTQUOhcWr7x9JvoRxT2MZw1T" crossorigin="anonymous">
    <script src="https://code.jquery.com/jquery-3.3.1.slim.min.js" integrity="sha384-q8i/X+965DzO0rT7abK41JStQIAqVgRVzpbzo5smXKp4YfRvH+8abtTE1Pi6jizo" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.14.7/umd/popper.min.js" integrity="sha384-UO2eT0CpHqdSJQ6hJty5KVphtPhzWj9WO1clHTMGa3JDZwrnQq4sF86dIHNDz0W1" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.3.1/js/bootstrap.min.js" integrity="sha384-JjSmVgyd0p3pXB1rRibZUAYoIIy6OrQ6VrjIEaFf/nJGzIxFDsf4x0xIM+B07jRM" crossorigin="anonymous"></script>
    <link rel="stylesheet" type="text/css" href="Style.css">
    <title>Weather Dashboard</title>
</head>
<body>
    <div class="navigation">
        <nav class="navbar navbar-expand-lg navbar-light bg-light">
            <a class="navbar-brand" style="background-color: rgb(255,255,255);" href="index.html">LATITUDE</a>
            <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNavDropdown" aria-controls="navbarNavDropdown" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNavDropdown">
                <ul class="navbar-nav ml-auto">
                    <li class="nav-item dropdown">
                        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdownMenuLink" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                            PLOTS
                        </a>
                        <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
                            <a class="dropdown-item" href="WebVisualizations/temperature.html">Max Temperature</a>
                            <a class="dropdown-item" href="WebVisualizations/humidity.html">Humidity</a>
                            <a class="dropdown-item" href="WebVisualizations/cloudiness.html">Cloudiness</a>
                            <a class="dropdown-item" href="WebVisualizations/wind.html">Wind Speed</a>
                        </div>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="WebVisualizations/comparison.html">COMPARISON</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="WebVisualizations/data.html">DATA</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link" href="https://github.com/VirginiaMwape/Web-Design_Challenge">REPO</a>
                    </li>
                </ul>
            </div>
        </nav>
    </div>
    <div class="container">
        <div class="row">
            <div class="col-lg-7 col-md-12">
                <div class="box" style="padding-bottom: 20px;">
                    <h3 class="title">SUMMARY: WEATHER PLOTS <br> (LATITUDE VS. X)</h3>
                    <hr>
                    <img src="Resources/assets/images/Fig1.png" class="vizualization rounded float-left" alt="Max Temperature Graph">
                    <p> The purpose of this project was to analyze how weather across 500+ cities across the world
                      changes as you get closer to the equator. To accomplish this analysis, OpenWeatherMap API was
                      utilized to assemble the dataset to create a representative model of weather across world cities.</p>
                      <br>
                    <p> Matplotlib was used to build a series of plots to showcase the relationships regarding several variables
                      of weather vs. latitude. Relationships analyzed included: Temperature (F) vs. Latitude, Humidity (%) vs. Latitude,
                      Cloudiness (%) vs. Latitude, and Wind Speed (mph) vs. Latitude.</p>
                      <br>
                    <p> Data and visualizations are are provided as part of the analysis, including explanations and descriptions
                      of trends and correlations.</p>
                </div>
            </div>
            <div class="col-lg-5 col-md-12">
                <div class="box">
                    <h3 class="title">VISUALIZATIONS</h3>
                    <hr>
                    <div class="container">
                        <div class="row" style="padding-bottom: 70px;">
                            <div class="col-6">
                                <div class="title">Latitude vs. Max Temperature</div>
                                <a href="WebVisualizations/temperature.html">
                                <img class="panel" src="Resources/assets/images/Fig1.png" alt="Max Temperature Graph">
                                </a>
                            </div>
                            <div class="col-6">
                                <div class="title">Latitude vs. Humidity</div>
                                <a href="WebVisualizations/humidity.html">
                                <img class="panel" src="Resources/assets/images/Fig2.png" alt="Humidity Graph">
                                </a>
                            </div>
                        </div>
                        <div class="row" style="padding-bottom: 70px;">
                            <div class="col-6">
                                <div class="title">Latitude vs. Cloudiness</div>
                                <a href="WebVisualizations/cloudiness.html">
                                <img class="panel" src="Resources/assets/images/Fig3.png" alt="Cloudiness Graph">
                                </a>
                                <!-- <div class="title">vs. Cloudiness</div> -->
                            </div>
                            <div class="col-6">
                                <div class="title">Latitude vs. Wind Speed</div>
                                <a href="WebVisualizations/wind.html">
                                    <img class="panel" src="Resources/assets/images/Fig4.png" alt="Wind Speed Graph">
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
    <footer> Web Design Challenge - Virginia Mwape </footer>
</body>
</html>
