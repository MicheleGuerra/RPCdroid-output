# RPCdroid-output

Example on Shazam
===============================
In this folder you can observe the output generated by RPCdroid on the Shazam app (screenshots are not in the folder due to space issues). With our concept of context usage related to user actions and GUI elements, we identified the microphone usage by this app when opening and not only when requesting the recording of the song to be recognized.

![Alt text](https://github.com/MicheleGuerra/RPCdroid-output/blob/main/readme-images/configuration/plot.png?raw=true "Title")

As you can see from the plot and the screenshot related to event 285237101, during the application startup it is already using the RECORD_AUDIO permission from the permission with id -78825927 (obviously the permissions were already accepted by default).

![Alt text](https://github.com/MicheleGuerra/RPCdroid-output/blob/main/readme-images/configuration/event-img.jpg?raw=true "Title")

The table below shows us other details about the event and thus the context of use of the microphone resource. From the description of the activity *com.shazam.android.activities.SplashActivity* we can see that it is the startup splash screen of the application.

![Alt text](https://github.com/MicheleGuerra/RPCdroid-output/blob/main/readme-images/configuration/table.png?raw=true "Title")
