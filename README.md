# VonageVideoCertificateProject

Hi Mark,

Here is my third project using TokBox by Vonage's OpenTok video service.

I wanted to run this project on two different computers, however I only have one PC with webcam, which is my work laptop computer.

As such, I scaled down the project and ran with this single HTML file. It is capable to run multiple sessions given the instructions as indicated below:

Clone or download the file (e.g. git clone https://github.com/max-schmidt92/VonageVideoCertificateProject.git). No need to install any NodeJS packages.

Change API key, Session ID and token from OpenTok. Quick access to these credentials, after logging in, can be found from this link: https://tokbox.com/developer/quickstart/

For the project, I have utilised the JetBrains Webstorm IDE to run or debug the project for the sake of simplicity. The required steps are as follows:

1. Right-click on the index.html file and hit "Debug" option. (You may get errors related to CORS policy from request/response headers, but it does not impact the video session.)

2. A chrome browser will appear with a video box. Allow Chrome or Firefox to access camera and microphone upon request.

3. Open an incognito window, copy and past the URL from the original chrome browser into the incognito window. You will see this warning message in the IDE:

![Press "Copy authorization URL to clipbord"](http://puu.sh/Fxkm4/977831cfc8.png)

4. Press the "Copy authorization URL to clipbord". Go back to the incognito window, paste the URL and hit enter.

5. Each window should now contain a mirrored video session from the same camera, as highlighted in the picture below:

![Mirrored images of me](http://puu.sh/Fxkny/f324fac580.jpg)

(If only one picture emerges in each browser window, try opening another tab in either the normal or incognito browser, and then close the previous browser.)

You should be able to get the expected result as shown above.

Best regards,

Max Topsholm
