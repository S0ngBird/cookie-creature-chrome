# cookie-creature-chrome
A really basic chrome extension for downloading youtube cookies for use with [yt-dlp](https://github.com/yt-dlp/yt-dlp).
It downloads cookies as a text file in Netscape HTTP cookies format, which can then be loaded into other applications as
necessary.

## Installation
Since this homebrewed and not on the chrome extension marketplace or whatever, this extension has to be installed by 
downloading the source code and loading it manually into your browser.

1. Download source code by selecting the "Code" dropdown and choosing the "Download ZIP" option
2. Unzip the code and take note of the folder you put it in
3. Manage your extensions by going [here](chrome://extensions/)
4. Enable developer mode by turning on the slider in the very top-right corner of the window
5. From the new menu options in the top-left of the window, select "Load unpacked"
6. Single-click the folder that contains the unzipped source code that you downloaded in step 1.

The extension should now be installed!

## Usage
Once the extension is installed, simply open it up from an existing youtube page where you're already logged in and 
click the big ol' "Download current cookies" button. It should download a small text file containing your cookies, 
which you can then pass into yt-dlp (or whatever you need those cookies for).

## Notes on the code
Most of the code is written in typescript, although this repo does include the compiled javascript as well just in case. 
I did use some references online to help me out a little bit with how to make the file download work OK. Otherwise though, 
it's my first real attempt to write anything in typescript, so it may look pretty jank from a more trained eye than mine.
