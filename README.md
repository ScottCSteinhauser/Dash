# Dash
Every year, first-responders issue a significant amount of alerts to save lost children, senior citizens, and and stolen vehicles. With an increasing amount of Americans using dash cams, we thought it'd make sense to combine optical character recognition (OCR) with these cameras in order to increase the success rate of the vehicles associated with these alerts being found.

# What it Does
This project is broken up into two components:

An intelligent dash-cam android app built using Java and Android Studio that uses OCR to scan the live camera feed for a set of license plates. If found, it reports its location, the license plate, and a time stamp to our database.

A [full-stack web app](https://github.com/imatson9119/DashWeb) intended for first-responders that pulls the reported data from a Firebase database and displays pertinent location data for each vehicle being searched for.

# How We Built it
We built the android app using Android Studio, Java, and an OCR text-recognition library. We used Firebase for our backend and communicated with it from the mobile app and web app using a REST API we developed. We used Angular and Google Maps API for our front-end to create a slick web app for first-responders.

# Try it out
The web app is available at [https://dash-66822.web.app](https://dash-66822.web.app), and the android app can be compiled from the GitHub source.

# Video
[![YouTube Link](http://img.youtube.com/vi/9Fl0UFbIA2c/0.jpg)](https://www.youtube.com/watch?v=9Fl0UFbIA2c "Dash")
