# Latmetio Weather App

This is the first verson of the weather forecasting app (or website, whatever you like). Now currently, I am working with my fellow web-designer to develope a "remake" of this app on React.js, powered with SPA technology.

## 1. Features
* Shows the current weather conditions at the particular time of the day
* Shows the forecast for the current day
* Shows the forecast for the 3 days ahead
* Has the automatic night theme
* Has diffent backgrounds for the particular weather condition
* Changes the texts, links, shadow colors according to the background theme

## 2. What I used:
* HTML5, CSS3. Yeah, nothing fancy
* Vanilla Javascript. Functions, working with DOM, Fetch API
* jQuery. I wanted to practice with AJAX technology
* Bootstrap UI. In particular, grids only
* Remix icons. For UI and weather icons
* Google Fonts. Roboto font for the app

## 3. Where do I fetch the data?
I fetch the data about the current weather from the OpenWeather Current Weather Data API.

Link: https://openweathermap.org/api

Due to limitations in free forecast API, I decided to use and fetch data about next 3 days from the http://hydromet.uz/, since they provide free and unlimited data from their forecast API. In addition, it was fun for the to combine 2 API calls and not to crash the site. While using this API, I worked with the XML. It was very interesting experience for me, but JSON is better for me)

## 4. Known Bugs
There is a bug with the Hydromet.uz API regarding the number of forecasted days. In the morning (till about 10: 00), the number of displayed forecasted days is 2, but then, it shows the forecast for the 3 days.

## PS
I know that the code isn't perfect and to be honest, I could have optimize it and clean it up. Maybe if I have some free time, I would do it. 

## Update 24/10/2021
Well, I got some free time and refactored the code. Now the old "untouched" legacy code could be found in "legacy" branch.

In new code, I am using ES5/ES6 synthax, removed jQuery as a dependency and removed the unnecessary legacy HTML code. 