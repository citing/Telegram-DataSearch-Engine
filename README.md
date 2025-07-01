# Telegram-DataSearch-Engine

This is made for home use and local use only.

Make sure you have python and GO lang installed

how to make a telegram bot, contact @BotFather on telegram and request to make a new bot. then after you made your bot take the token and do what is under this
go to the bot.py file and get your bot token and replace it in the place it says to. then save the file as it is

i highly suggest if your databreach file is above 20 gb in a single text file you use GSPLIT to split the file into 5gb to 10gb per file then upload the split up files for better speeds. If you split your large files into smallers files like i said, around every 100gb of data the bots searches will slow down by about a minute, it works fine with any amount of data for the most part i highly doubt anyone is going to put 600gb of data and make it a problem
i have my bot running on around 300gb of TLO data and it works just fine with speeds averaging arouind 3 minutes per search


HOW TO RUN.
open "cmd" in the folder of each script file and put these.

go run main.go

python bot.py !THEY HAVE TO STAY OPEN WHILE UR USING THE BOT!

How to upload ur files so the bot can read it.
use powerchell 7 and type in your file directery to the .txt file

example-
*curl -X POST -F "file=@C:/Users/YourPcUser/Desktop/botproject/go-backend/breach_data/criminal_export.txt" http://localhost:8080/upload*

!USE THIS ONE! COPY ALL OF IT!
curl -X POST -F "your directory" http://localhost:8080/upload

