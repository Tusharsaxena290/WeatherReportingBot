# Weather Reporting Bot
</br>

## What is **OpenWeatherMap**?
</br>
OpenWeatherMap is an online service, owned by OpenWeather Ltd, that provides global weather data, including current weather data, forecasts, nowcasts and historical data, utilising meteorological broadcast services and raw data from airport weather stations, radar stations and other weather stations.
</br>
Openweather NWP (numerical weather prediction) allows to calculate weather data for any location. We use proprietary convolutional neural network that collects and processes wide range of data sources to cover any location and consider the local nuances of climate. 

ML technology allows us to reach resolution about 500 m and very high accuracy between 90% and 100% with inaccuracy about 1%. Amongst data sources we feed to the NWP are 82,000 weather stations spread globally; national meteorological agencies (NOAA, Environment Canada, Met Office, etc.), radars, weather satellites.

</br>
</br>

<img width="461" alt="Screenshot 2021-01-12 175439" src="https://user-images.githubusercontent.com/53862641/104314340-48d14500-54ff-11eb-800f-3ffeacfdcff4.png" align="centre">

</br>

## What is eSpeak?
</br>
The eSpeak NG is a compact open source software text-to-speech synthesizer for Linux, Windows, Android and other operating systems. It supports more than 100 languages and accents. A command line program (Linux and Windows) to speak text from a file or from stdin. A shared library version for use by other programs.
</br>
</br>

## Prerequisites
</br>

- Raspberry Pi 3 Model b/B+
- 16 GB SanDisk class 10 SD Card
- Card reader
- Power Adapter – 5V 2Amps
- USB B-Type Cable
- Laptop Speaker/Headphones
</br>
</br>

### Steps to get the API
</br>
1.Create an account on OpenWeather.
</br>
After signing in you will be re directed to this.
</br>
<img width="733" alt="s1" src="https://user-images.githubusercontent.com/53862641/104316505-94392280-5502-11eb-9679-16e3b9a8b7a6.png">
</br>
2. Click on Pricing and opt for the free API available.
</br>
<img width="724" alt="s2" src="https://user-images.githubusercontent.com/53862641/104316712-e37f5300-5502-11eb-8bfa-3617b55523cb.png">
</br>
</br>

## Open the terminal on Raspberry Pi.

1. Execute the command stated below to enable 3.5mm Audio jack in RPI. 

``` bash
sudo raspi-config

```

</br>

2. Click System Options.
</br>

<img width="509" alt="system" src="https://user-images.githubusercontent.com/53862641/104317319-d020b780-5503-11eb-8f97-c40b523e6043.png">
</br>

3. Install eSpeak by executing the command stated below on the terminal

``` bash
susdo apt-get install espeak
```

</br>

## Execute the code stored in the file named WeatherReporter.py

</br>
</br>

<img width="184" alt="s3" src="https://user-images.githubusercontent.com/53862641/104317934-afa52d00-5504-11eb-9dec-b66f666a8c66.png">














 






