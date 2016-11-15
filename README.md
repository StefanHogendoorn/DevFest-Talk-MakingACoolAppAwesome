# DevFest-Talk-MakingACoolAppAwesome
Code / Walkthrough for the 2016 DevFest / GDG Talk about adding Firebase and Machine Learning to a web app to make it from a (somewhat) cool app into an Awesome app.

## Story line
So we've created an application that gets tweets on a certain topic you type and shows this in a list. It is cool because it is using Polymer to display a Twitter(c) feed. Well... turns out, not so many people think this is cool because all in all, it just shows a Twitter feed.
## Overal structure of the application
The application has a web front-end created using Polymer and the polymer scaffold.
## Making it a bit cooler - step 1
Wouldn't it be great if you could store the tweets you collect so you can later quickly recover them?
We do this by adding Firebase to our application. In Polymer we just add a couple of elements to show the data coming from Firebase instead of the API call

## Technology used in this demo
- Polymer
- Firebase
- Google Cloud Vision API
- Google Cloud Natural Language Processing

# What will this teach/show you?
It will show you how easy it is to add Firebase and Machine Learning to your project.

# How to use this code
## Prerequisits
- Your favorite Web and Pyhton editor... yes, vi counts too.
- Download Python 2.7 (not sure if this will work with Python 3, but feel free to give it a try)
- Download Flask and Tweepy
- Download the Polymer command line (https://www.polymer-project.org/1.0/docs/tools/polymer-cli)
- Create a Firebase project (https://console.firebase.google.com)
- Create a Google Cloud Platform project (https://console.developers.google.com)
- In the Cloud Platfom project, enable the Vision API and Natural Language API


