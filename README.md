# LSTM-music-generator

This was a project I did. I was heavily inspired by this implementation of the LSTM music generator
https://github.com/PacktPublishing/Python-Deep-Learning-Projects/tree/master/Chapter06
from which I only added some more embedings and tweaked the dropout values. 

I also included a web scraper for scraping MIDI files from the website 
www.freemidi.org
You will need the selenium web driver to do this as the website required to manualy click a link which was only emulated by a web driver like Selenium


This project was trained on google collab as it definitely needs a GPU to train. With the provided hardware I was able to train up a decent model in 5-6 hours.

You can play with the notebook and most of all how and what kind of instruments I get in the begining. I experimented with feeding the model only piano pieces but also guitar and a combination of them both.
This is the part that will most influence the sound produced by the model on top of the original data that you feed it. In my case, I chose to train the model to play BLues as it has a relatively simple structure to learn.

I have included some of the results as midi files. If you have any kind of music software like Garage Band or Ableton I reccomend using those as the Midi instruments are of very high quality
