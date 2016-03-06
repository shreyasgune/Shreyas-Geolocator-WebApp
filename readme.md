# Shreyas's Geolocator

## Synopsis
This is  a sample App I made to test out how easy it is to deploy a simple Web App based on Web.py framework. It is a simple app using a Google's Geolocation Engine

## Code Example

There is no specific code example, because the code itself is pretty straightforward. If you have trouble understanding it, email me at : [shreyas.enug@gmail.com](shreyas.enug@gmail.com)

## Motivation

This project exists simply because I wanted to create something from the ground up and see how easy-hard it was to deploy. There were a few glitches, but overall I'm satisfied with it.

## Installation

This is where it might get tricky. Now, if you are running a local copy of this on your machine, it matters what machine are you using it on. 
I coded this and ran this on Windows. I could've VBOX'd it but I knew it was going to be a bigger challenge doing it on Windows. 

Make sure you have all these installed : 
'''
web.py==0.37
Jinja2==2.6
Werkzeug==0.8.3
gunicorn==0.14.2
wsgiref==0.1.2
'''

In Windows ::
Make sure you make these changes, else routing and template rendering wont work.
'render = web.template.render('<Your Full Path>/<yourapp>/templates/')'

else keep it this :
'render = web.template.render('templates')'
and for the love of everything that means dear to you, don't do this  : 'render = web.template.render('\templates')' That slash was so problematic. 

To run the server : 'python app.py <PORTNUMBER>' from your Terminal
To Close the server : Ctrl+C OR Ctrl+Z 

## API Reference
Mostly Google APIs : Fonts , Geolocation and Mapping. They've made things really easy. The more I do these projects, the more I learn how nifty their APIs are.


## Tests

No test cases were written. I know I should've have, but I just wanted to hack it enough to make it work.

## Contributors
If you want to contribute or add to it or make it better, more readable, go for it. Tweet me issues if you can  : [@shreyaslumos](https://www.twitter.com/shreyaslumos) 

## License

I don't know how these open source licenses work (note to self , go read up on it.). As far as I am concerned, its all open for everyone, forever. Go bonkers.
