# WTSIL
Sends me a text of the temperature, weather conditions, what time I should leave my house to arrive at school on time, and travel time.

To use: Include a config.py file in the project folder with the following format:

--
**From Twilio**

account_sid = ""

auth_token = ""


**From openweathermaps.org**

keyWeather = ""

city = ""


**From Google API. Origins/destinations are in 'Street#+RoadName+City+Province/State'**

keyMaps = ""

origins = "origins="

destinations = "&destinations="


**From Twilio. Phone1 = your phone number, phone2 = phone number from Twilio service**

phone1 = ""

phone2 = ""

--

Actual arrival time is in unix format, so use a unix converting tool such as http://www.epochconverter.com/ to find the proper time.
This code can be expanded to run on an Amazon AWS or DigitalOcean server.

**Important Links:**

http://openweathermap.org/

https://www.twilio.com/

https://console.developers.google.com/
