# intellistar-emulator
A web application that displays weather information in the same visual presentation as the cable headend unit [Intellistar](https://en.wikipedia.org/wiki/IntelliStar).

## Overview
This is a local forecast segment that airs on The Weather Channel called the "Local on the 8s". The name is because it airs at timeslots that end in "8" (9:28, 2:48, etc.). The forecast is approximately a minute long and provides information on current and forecasted weather conditions. This type of forecast started in 1982 using WeatherStar units. It was later upgraded to Intellistar in 2003 and recieved various graphic changes over the years. This emulator uses the style that started in 2013.

## Instructions
## Option 1 (easier)
1. Visit: <https://liuwoodscode.github.io/intellistar-emulator/>.
2. Enter zip code
3. Click start
4. Press F11 for fullscreen

## Option 2 (more customizable)
1. Extract all contents into folder
2. Run index.html in Google Chrome
3. Enter zip code
4. Click start
5. Press F11 for fullscreen

## Features
Most of core animation and logic has been replicated including severe weather alerts, forecast descriptions, crawl text, and the Doppler radar map.

*Some of these features are temporarily not working due to the discontinuation of WU's API*

## Looping
To enable or disable looping, click on the TWC logo in the info-bar in the top-left corner of the emulator.

To get looping working properly, you may (as of Chrome M66) have to go to chrome://flags#autoplay-policy (Autoplay Policy) and change it to `User gesture is required for cross-origin iframes` or `No user gesture is required`  

## Background
Once you have downloaded the repo, go into js/MainScript.js and `change getElement('background-image').style.backgroundImage = 'url(https://i.imgur.com/4f9Qb0j.jpg';` to something `like getElement('background-image').style.backgroundImage = 'url(https://picsum.photos/1920/1080';`

