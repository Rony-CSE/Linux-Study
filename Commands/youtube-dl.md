install :

# sudo apt-get install youtube-dl

# sudo apt-get install ffmpeg



video download:

# youtube-dl [ URL ]

# youtube-dl -F [ URL ] (to check available formats)

# youtube-dl -f [ format number ] [ URL ]

# youtube-dl --yes-playlist [ URL ]

$ youtube-dl -cit [ URL ]

audio download:

# youtube-dl --extract-audio --audio-format mp3 <video URL>




Is there any problem with youtube-dl then do the following:


# sudo apt-get remove -y youtube-dl

# sudo wget https://yt-dl.org/latest/youtube-dl -O /usr/local/bin/youtube-dl
# sudo chmod a+x /usr/local/bin/youtube-dl
# hash -r

# sudo youtube-dl -U
# sudo apt-get install ffmpeg
