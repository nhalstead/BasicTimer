# BasicTimer
This is a small Windows C# Timer that allows People to create a timer that can countdown a play a sound notifying the user that the time is up. 

Using the "Define Audio" button you can change the music for that session. Otherwise you can click "Default Sounds" and it will reset the file back to the default. If you wish to change it so it will play that file everytime and not just play it when you Define it you can go and delete the file "alarm_sound.wav" and replace it with another "alarm_sound.wav" and the system will play that file.


## Audio Object
The sound comes from a WindowsMediaPlayer Object, so any file that WMP supports it can play. You can play any file type you want by using the "Define Audio" button.

## My Plans
I am planning on making it detect any alarm_sound.(mp3, wav, etc) media types and use them in prority. When I have a chanse I will add it in.
