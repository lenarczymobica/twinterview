# twinterview The project code - TW
<p>
## The app requirements:
</p>

### General information:<br />
The app downloads wheather data from wheather service - http://api.openweathermap.org/data/2.5/forecast/daily?mode=json&units=metric&cnt=7&APPID=15646a06818f61f7b8d7823ca833e1ce&zip=94043<br />
It provides data for next 7 days including current day.<br />
Icon resource: http://openweathermap.org/img/w/#icon.png - for example http://openweathermap.org/img/w/04n.png - #icon is in json<br />
Downloaded wheather data should be persisted<br />
Zip code is hardcoded and if you create settings screen should be stored somewhere<br />

## There are 3 screens within the app.

### Main Screen:
TW-1. There is a list with wheather information items for next 7 days - zip code can be hardcoded<br />
TW-2. Each item contains icon - state of wheather,  day description in format MM DD, YYYY, whether desciption, max temperature, min temperature<br />
TW-3. The app contains toolbar with title: name (country) - Mountain View (US) - according to screen shot<br />
TW-4. Tapping on wheather item, the user is forwarded to Details Screen<br />
TW-5. The app contains toolbar with menu with Settings item.<br />
TW-6. Tapping on Settings item, the user is forwared to Settings screen<br />
![alt text](screens/main.png "Main Screen")

### Details Screen - screen shot details.png:<br />
TW-7. The screen contains toolbar with title: name, day in format: Day, Month, DD, YYYY - according to screen shot<br />
TW-8. The toolbar contains <- navigation icon<br />
TW-9. Details screen contains: icon, whether description, max temperature, min temperature<br />
![alt text](screens/details.png "Details Screen")

### Settings screen - screen shot settings.png:<br />
TW-10. The sceen contains toolbar with title: Settings and back icon <-<br />
TW-11 Settings screen contains: City ZipCode, EditText with hint City ZipCode, accepting only Numbers - zip code is changing in settings screen<br />
![alt text](screens/settings.png "Settings Screen")
