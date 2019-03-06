[![Mentioned in Awesome-Selfhosted](https://awesome.re/mentioned-badge.svg)](https://github.com/Kickball/awesome-selfhosted#personal-dashboards)

# simple-dash

Try the Demo here: https://swagielka.github.io/simple-dash/

A simple, fully responsive Dashboard to forward to the services of your choice! Ideal for Desktop and mobile usage!
Add all of your services, whether you host them yourself or not and display them as neat Icons from the FontAwesome libary.
simple-dash is made to be as simple and minimalistic as possible. (The goal was to create a dashboard even my mom could use!) :)
Based on: https://github.com/thetomester13/homepage

This project uses:
- [Font Awesome](http://fontawesome.io/icons/)
- [Trianglify](https://github.com/qrohlf/trianglify)

## Screenshots

![Homepage Desktop](https://raw.githubusercontent.com/Swagielka/simple-dash/master/example_img/homepage-desktop.jpg)
![Homepage Mobile](https://raw.githubusercontent.com/Swagielka/simple-dash/master/example_img/homepage-mobile.jpg)

## To Use

Copy the config.sample.json file and rename to config.json. Be sure to update the fields as you see appropriate.

## Configure Homepage

> `items` : The menu will scale to the amount of items you want to display. Insert any link you'd like, or {{cur}} for the current URL of the page. Choose icons from [Font Awesome](http://fontawesome.io/icons/)

```json
{
    "title" : "Your Homepage Title",
	"items" : [
		{
			"alt" : "Github",
			"icon" : "fab fa-github",
			"link" : "https://github.com/Swagielka"
		},
		{
			"alt" : "Twitter",
			"icon" : "fab fa-twitter",
			"link" : "https://twitter.com/Kukielka_"
		},
		{
			"alt" : "Docker Hub",
			"icon" : "fab fa-docker",
			"link" : "https://hub.docker.com/u/kukielka/"
		}
	]
}

```
