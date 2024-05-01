# Weather App

This is a simple weather app that allows you to retrieve weather information for a specified location or based on latitude and longitude coordinates. It uses the OpenWeatherMap API to fetch weather data and displays weather icons from Remix Icon and Google Drive.

## Tutorial
Full Step by Step tutorial 👉🏻 [click here](https://youtu.be/X3EcVqyef14)

## Full Source Code
The complete source code can be found at the following link: 👉🏻 [click here](https://rb.gy/06lgrk)

## Setup

To use this weather app, you need to include the Remix Icon CSS and set up the OpenWeatherMap API.

### Remix Icon CDN

Include the Remix Icon CSS in your HTML:

```html
<link href="https://cdn.jsdelivr.net/npm/remixicon@3.5.0/fonts/remixicon.css" rel="stylesheet">
```

### API Url

You will need to sign up for an API key from [OpenWeatherMap](https://openweathermap.org/api) and replace `${apiKey}` with your actual API key in the following API URLs:

#### Get Weather by City Name

```html
https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=${apiKey}
```

#### Get Weather by Latitude and Longitude

```html
https://api.openweathermap.org/data/2.5/weather?lat=${latitude}&lon=${longitude}&units=metric&appid=${apiKey}
```

Make sure to replace `${city}`, `${latitude}`, and `${longitude}` with the actual city name or coordinates and `${apiKey}` with your API key.

### Weather Icons

The app uses weather icons hosted on Google Drive. Here are the icon URLs:

- ![Clear Sky](https://drive.google.com/uc?export=view&id=13TlzPFrICsSEB3llo6PWuywWpoL6ywxb) - Clear Sky
- ![Few Clouds](https://drive.google.com/uc?export=view&id=13eqt-OgtVphxXYpIHd9Q7QOBNocK0Onq) - Few Clouds
- ![Scattered Clouds](https://drive.google.com/uc?export=view&id=13Z9FbAC1FJ-ptr55vUWUufLBCrhgjbF1) - Scattered Clouds
- ![Broken Clouds](https://drive.google.com/uc?export=view&id=13YVPMlryJ3168jk-VR_zfTvVBL6Xeaqs) - Broken Clouds
- ![Rain](https://drive.google.com/uc?export=view&id=13TVP9iuZz8A9cf3OtJCgTmeS9AtJ-B3R) - Rain
- ![Thunderstorm](https://drive.google.com/uc?export=view&id=13YoLrgIqfw6UHTu0x4yqTRLIyCbT1O6e) - Thunderstorm

## Usage

You can integrate this weather app into your website or application to display weather information for a specific location or based on coordinates. Simply make API requests to the provided URLs and use the returned data to display weather conditions and icons accordingly.

## License

This weather app is provided under the MIT License. Feel free to use, modify, and distribute it as needed.

## Preview
![Realtime weather App](https://github.com/Aarzoo75/Real-Time-Weather-App/assets/59678435/08e62443-36a0-431e-b3db-c7a14e64bfdd)

