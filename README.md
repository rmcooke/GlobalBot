# GlobalBot
Work on extending the Google Assistant - Richard Cooke

For a prototype of the bot I have chosen to extend the Google Assistant platform. Google assistant is a voice controlled assistant available on latest versions of iPhone and Android.
A client for google assistant can also be built on any platform where Python is fully supported. I have built one initially on Anaconda under windows and have shared the environment.yml file here to ensure a compatible Python environment when we are extending it.

For prototyping, I have used IFTTT which can accepgt triggers from Google Assistant. For now the commands I have added to my bot have been pretty simple and I am now investigating how we could make a request to a server using the voice command to a web service using JSON. This web service will be our interface to the bot. We can keep it pretty simple for starters maybe just using a lookup table of answers mapped to questions. 
