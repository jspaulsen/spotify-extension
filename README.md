# spotify-extension
Spotify Extension for Sammi

## Setup

To setup the extension, click into and run the `Setup` button. It will open a browser and prompt you to authorize a spotify application.

![alt text](images/spotify.png)

Confirm and it will redirect you to a webpage which returns your refresh token. Copy this token and paste it into the prompt.

![alt text](images/token.png)

Once inserted, it (should) update the status button; if not, check the variable widndow:

![alt text](images/variables.png)

## Track Payload

If using a non-persistent button, you must "wait for variable"
If a value doesn't exist / isn't returned, return is 0

###  Track Payload
![alt text](images/image.png)
