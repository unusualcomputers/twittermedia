# fshlb, gifko & subsYeah

Windows utilities used to create twitter friendly videos. 

__gifkoPro__ takes as input an existing video (something you made or downloaded, maybe from youtube or wherever) and creates a short snippet of it (you choose from and to values) in a format that works nicely with twitter. mp4 version will have sound in it, gif will not.

__subsYeahPro__ takes as input a video and an .srt subtitles file and hardcodes the subtitles into the video so that it's only one file, suitable for uploading to social networks.


__fshlbPro__ takes as input a picture (ideally a png file in one of the sizes mentioned below) and an audio file and combines them into an mp4 video suitable to upload to twitter with the picutre in the background and audio visualisation in the foreground.

It is somewhat configurable and you can save configurations for later use, the most common ones are already supplied (for the three common file sizes).
The usage is simple, when you run it, it should all be quite intuitive, but there are explanations in tooltips, just hover mouse over fields on the screen.

# Installation

All utilities here use __ffmpeg__ , a wonderful free library for dealing with videos. 

## The easy way

The easiest way to do this is to download entire folder with everything already setup from [here for 64 bit windows](https://mega.nz/#!yPpiBYKR!J3od6zwqdKg47B3Jm6VQQA7PSQYqWBwawtxh-VZ_Tf4) and [here for 32 bit windows](https://mega.nz/#!iOw1EKaZ!QdchZ1CjjQPzxNKH7FAfzCPD7RRNadzKihyrzyxN-aI). If you are not sure which, try 64 bit first. Once downloaded, unzip the file and you will see the three tools in the new folder called twittermedia, just double click on them to start them.
For this you need to trust us, which may be difficult and we take no offence in that. If it helps, the folder contains all the same things you would have if you followed the hard way instructions.

## The hard way

To install things manually:

* Create yourself a new folder for all this, call it what you like we call it 'twittermedia'
* Download our source code - click on the green button that says "Clone or download" to the top right of this page.
* Unzip it and copy all the files from it to your new folder
* Download ffmpeg - from [here](https://ffmpeg.zeranoe.com/builds/), make sure you choose "Static" under Linking
* Unzip it, then rename the new folder this created to 'ffmpeg' (has to be called this, and without quotes)
* Copy your new 'ffmpeg' folder to the folder that you created and where you copied the rest of the files
* Now check your folders are all ok:
    * Your new folder should contain all the files you got from us at the top level (not in another subfolder). Move them if you need to.
    * Your new folder should contain a subfolder ffmpeg which should contain subfolder 'bin'. This structure is important, won't work otherwise, move things if you need to.

# How to use

Most things are going to be quite obvious, but every field has tooltips, float your mouse over everything and read these, it really helps. One thing that is often confusing is how to input start and end times for things - follow the tooltip and try it out a bit if things don't work. Error messages are quite rubbish, but is things fail this is the first thing to try.

To add subtitles to your video you will need an srt file with subtitles in it. There are very nice free tools to download to do this, google them. For short films you can easily create these files manually without any additional software, there is a nice guide [here](https://www.3playmedia.com/2017/03/08/create-srt-file/) or google something like 'how to create srt files manually'. It is really, really easy once you try it. 


Optimal video sizes for twitter are 320x180, 640x360 and 1280x720. The quality of outputs will be best if pictures or video inputs are one of these.

Note that twitter imposes limits on video sizes - they must be shorter than 2m20s and smaller than 512Mb (more details [here](https://support.twitter.com/articles/20172128#video-formats)).


Please let us know if you used them and most certainly if they did not work ( unusual.computers(at)gmail.com ).


