# Flutter Weather ⛅️

This is a simple Flutter application used as a basis to build upon in a pair programming session.

## Current architecture

We have a running app that grabs your current location and presents the local weather. Nice, things are lookin' bright ☀️

## Goals

We'd like to be able to see the forecast for the next 6 days. But when we navigate to our forecast screen, we no longer have our location data.

Things just became a little cloudy ☁️

Todo:

- [ ] Build a way to retain our geolocation when moving between screens
- [ ] Fix the layout issue on ForecastPage
- [ ] Add the icon to the forecast items

Extra:

- [ ] Convert the API response of **5 day / 3 hour** into **5 days**

## Info

Getting current weather data

```
POST: https://api.openweathermap.org/data/2.5/weather?lat={lat}&lon={lon}&appid={API key}

Response:
200
{
  
}
```
[[Current weather data resource](https://openweathermap.org/current)

```
GET: https://api.openweathermap.org/data/2.5/forecast?lat={lat}&lon={lon}&appid={API key}

Response:
200
{
  
}
```

[5 day / 3 hour forecast resource](https://openweathermap.org/forecast5)

## Retro

What would you do differently given infinitely more time?

How would you improve the project structure?

What do you think could be improved?

