[weather]
<!DOCTYPE html>
<html>
<head>
  <title>Weather App</title>
  <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
  <div id="weather-container">
    <h2>Weather App</h2>
    <div id="location-container">
      <input type="text" id="location-input" placeholder="Enter location">
      <button id="submit-btn">Get Weather</button>
    </div>
    <div id="weather-info">
      <div id="current-weather"></div>
      <div id="forecast-weather"></div>
    </div>
  </div>
</body>
</html>
*********style.css***********
#weather-container {
  text-align: center;
}

#location-container {
  margin-top: 20px;
}

#location-input {
  padding: 5px;
}

#submit-btn {
  padding: 5px 10px;
  margin-left: 10px;
}

#weather-info {
  margin-top: 20px;
}

#current-weather {
  font-weight: bold;
}

#forecast-weather {
  margin-top: 10px;
}
