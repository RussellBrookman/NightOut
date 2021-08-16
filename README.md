# NightOut ((remember to hide API key))

This site is designed to let a person know what is going on in a particular city. It can be used to plan an evening for a date or, if you're traveling into a new city, can be used to find out what's going on localy. The software uses three ajax API calls/promises (Application Program Interface) to collect information and has a limiter of 10 events per request. The first is from Eventful in order to provide information about local events and provide links leading the user to the origional listing. The second call is provided to show a clickable screenshot which will lead to a YouTube video about the event you are interested in. The last call is to openweathermap.org which returns local weather information about the requested city. 
	

# Prerequisites

* http-server
* npm


# Dependencies

* API calls
* API promises
* Bootstrap
* jQuery
* jsdelivr


# Command line Directions:

1. cd into this file

2. On first run only:
	sudo npm i -g http-server
	If this command doesn't work try this..
	npm i -g http-server

3. npm install

4. npm start

5. In the browser type:
	http://localhost
		or
	127.0.0.1:80
		or
	http://10.0.0.134:80


6. If you wish to stop your local host from running this website.. press Ctrl-C


# Site Directions: 

1. Type in a possible event you would like a suggestion or information on. All information is localized.
	(example: movies, music, bar, concert)
	
2. Type in a place you would like to search in. 

3. Look at the listings and the weather report. Click on any eventful link or YouTube video
