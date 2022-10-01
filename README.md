# Machine-Learning-Diploma-Mid-Project
<a href="https://drive.google.com/file/d/1r6V56jGgRVHLU0ThgFt5EuuS-hhkRV-w/view?usp=sharing">Rain In Australia Video</a>
# Introduction:
The issue of Climate Change is threating the existence of all humanity, it includes rising sea levels, ecosystem collapse and more frequent and severe weather. Rising temperatures from human-caused greenhouse gas emissions affects planet-wide systems causing drought and severe heat.<br>
The goal of the proposed project is to predict whether there will be rain in the next day in Australia based on the previous data gathered between 2008 and 2017, based on RainTomorrow feature we can extract a feature to predict whether it will rain during the season or not, also the rainfall feature can be used to extract an output feature that can predict the amount of water expected in a certain season.<br>
The ability to predict rain and the amount of the rain will help farmers plan which crops to grow at which time, which will help decrease food shortage and sustain stable food supplies.
# Features:
<ul>
<li>Date: The date of observation.</li>
<li>Location: The common name of the location of the weather station.</li>
<li>MinTemp: The minimum temperature in degrees Celsius.</li>
<li>MinTemp: The minimum temperature in degrees Celsius.</li>
<li>MaxTemp: The maximum temperature in degrees Celsius.</li>
<li>Rainfall: The amount of rainfall recorded for the day in mm.</li>
<li>Evaporation: The so-called Class A pan evaporation (mm) in the 24 hours to 9am.</li>
<li>Sunshine: The number of hours of bright sunshine in the day.</li>
<li>WindGustDir: The direction of the strongest wind gust in the 24 hours to midnight.</li>
<li>WindGustSpeed: The speed (km/h) of the strongest wind gust in the 24 hours to midnight.</li>
<li>WindDir9am: Direction of the wind at 9am.</li>
<li>WindDir3pm: Direction of the wind at 3pm.</li>
<li>WindSpeed9am: Wind speed (km/hr) averaged over 10 minutes prior to 9am.</li>
<li>WindSpeed3pm: Wind speed (km/hr) averaged over 10 minutes prior to 3pm.</li>
<li>Humidity9am: Humidity (percent) at 9am.</li>
<li>Humidity3pm: Humidity (percent) at 3pm.</li>
<li>Pressure9am: Atmospheric pressure (hpa) reduced to mean sea level at 9am.</li>
<li>Pressure3pm: Atmospheric pressure (hpa) reduced to mean sea level at 3pm.</li>
<li>Cloud9am: Fraction of sky obscured by cloud at 9am. This is measured in "oktas", which are a unit of eigths.</li>
<li>Cloud3pm: Fraction of sky obscured by cloud (in "oktas": eighths) at 3pm.</li>
<li>Temp9am: Temperature (degrees C) at 9am.</li>
<li>Temp3pm: Temperature (degrees C) at 3pm.</li>
<li>RainToday: Boolean: 1 if precipitation (mm) in the 24 hours to 9am exceeds 1mm, otherwise 0.</li>
<li>RainTomorrow: The amount of next day rain in mm. Used to create response variable RainTomorrow. A kind of measure of the "risk".</li>
</ul>
<h1>Data</h1>
<p>Link: <a href='https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package'>Rain in Australia</a></p>
<h3>Preprocessing:</h3>
<ul>
<li>Handle Missing Values</li>
<li>Feature Extraction</li>
<li>Detecting Outliers</li>
  <ul>
    <li>Handling Outliers</li>
  </ul>
<li>Split Data into Train and Test</li>
<li>Handle Imbalance</li>
<li>Feature Scaling</li>
</ul>
<h1>Questions:</h1>
<ul>
<li>Does having rain today have an effect on rain?</li>
<li>Does Minimum Temp have an effect on rain?</li>
<li>Does Maximum Temp have an effect on rain?</li>
<li>Does Sunshine have an effect on rain?</li>
<li>Does WindGustSpeed have an effect rain?</li>
<li>Does Humidity have an effect on rain?</li>
<li>Does Pressure have an effect on rain?</li>
<li>Does Minimum Temp have an effect on rainfall?</li>
<li>Does Maximum Temp have an effect on rainfall?</li>
<li>Does Sunshine have an effect on rainfall?</li>
<li>Does WindGustSpeed have an effect on rainfall?</li>
<li>Does Humidity have an effect on on rainfall?</li>
<li>Does Pressure have an effect on rainfall?</li>
</ul>
