# WearWeather

This is an Android app that shows current weather and predicts climatic conditions for a particular pin code or area which could be changed in the settings. The weather data is provided by Openweathermap API. It includes a detailed view of Windspeed, direction , Pressure and humidity. This includes a watch face that is automatically installed in the android wear when the user installs Sunshine App on the phone.

<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/images/circle.png" height=298 width =288/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/images/circle_ambient.png"/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/images/square.png"/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/images/square_ambient.png"/>

<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/Screenshots/Screenshot_20161030-194148_framed.png" height=480 width =270/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/Screenshots/Screenshot_20161030-194153_framed.png" height=480 width =270/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/Screenshots/Screenshot_20161030-194201_framed.png" height=480 width =270/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/Screenshots/Screenshot_20161030-194215_framed.png" height=480 width =270/>
<img src="https://raw.githubusercontent.com/aashishvanand/WearWeather/master/Screenshots/Screenshot_20161030-194220_framed.png" height=480 width =270/>


##What is it?

This is an Android wear watch face for an existing Android weather app.

##Why this Project?

Android Wear is an exciting way to integrate your app more directly into users’ lives. As a new developer, it will be important for you to understand how to perform this integration. This project gives you an opportunity to design a companion app for Sunshine, tying it to a watch face in order to enrich the experience.

##Platform and Libraries Used

- Android SDK 21 or Higher
- Build Tools version 23.0.3
- Android Support AppCompat 23.2.1
- Android Support Annotations 23.2.1
- Android Support GridLayout 23.2.1
- Android Support CardView 23.2.1
- Android Support Design 23.2.1
- Android Support RecyclerView 23.2.1
- Google Play Services GCM 8.4.0
- Google Play Services Wearable 8.4.0
- BumpTech Glide 3.5.2

## Open Weather Map API Key is required.

In order for the Sunshine app to function properly an API key for openweathermap.org must be included with the build.
We recommend that each student obtain a key via the following [instructions](http://openweathermap.org/appid#use), and include the unique key for the build by adding the following line to [USER_HOME]/.gradle/gradle.properties
`MyOpenWeatherMapApiKey="<UNIQUE_API_KEY">`
For help migrating an existing repo (fork or clone prior to 10/18/15), please check out this [guide.](https://docs.google.com/document/d/1e8LXahedBlCW1_dp_FyvQ3ugUAwUBJDuJCoKf3tgNVs/pub?embedded=true)

##Attribution

The weather data is provided by the [Open Weather Map API](http://openweathermap.org/api)
The weather app code was provided by [Udacity](https://github.com/udacity/
Advanced_Android_Development/tree/7.05_Pretty_Wallpaper_Time).  
