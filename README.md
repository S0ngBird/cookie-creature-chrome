# cookie-creature-chrome
A really basic chrome extension for downloading youtube cookies for use with [yt-dlp]("https://github.com/yt-dlp/yt-dlp")

## Pre-requisites
The only pre-reqs for this are cloning/downloading the repo, and loading it unpacked
as a new chrome extension. For instructions on how to load an unpacked extension, 
see [here](https://superuser.com/a/252990) (see the "Folder" instructions in that answer).

## Usage
Once the extension is loaded, simply open it up from an existing youtube page where
you're already logged in and click the big ol' download button. It should download a small
text file containing your cookies, which you can then pass into yt-dlp.

## Notes on the code
Most of the code is written in typescript, although this repo does include the compiled 
javascript as well just in case. I did use some references online to help me out a 
little bit with how to make the file download work OK. Otherwise though, it's my first 
real attempt to write anything in typescript, so it may look pretty jank from a more 
trained eye than mine.
