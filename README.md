if there are any suggestions/ideas/issues please please please open a Issue
# use voicemeeter to sing karaoke on teamspeak
first you need to install voicemeeter banana. [Download from Here](https://www.vb-audio.com/Voicemeeter/banana.htm)

1. in voicmeeter you first need to select you input device where "mic here" is pointing and the output 
2. (headphones) where "phones here" is pointing
3. then in voicmeeter select the A and B buttons like shown in the image (A is physical out and B is virtual)

4. then in th A1 selection next to the "phones" speech bubble select your output device
![enter image description here](https://i.imgur.com/rPb3EMS.png)
6. after that you need to select  "voicemeeter input" as the playback device in TeamSpeak
7. and "voicemeeter **AUX** output" as the capture device in teamspeak.

after that, every sound YOU can hear, EXCEPT what people in teamspeak say, will get mixed together with the your mic and then sent to teamspeak. 
basically people will be able to hear everything you hear with your voice

TEST: use teamspeaks test microphone checkbox to hear everything you are "saying" which should be all mic audio + what yo ucan hea (music/videos/games..)
errors: 
1. there is a constant loop: voicemeeter gets teamspeak audio in a channel that is connected to "voicemeeter AUX output"
2. you cant hear the music/video... : voicemeeter doesnt transmit the audio it picks up from your pc, make sure the windows default audio device is set to "voicemeeter input"

beacause teamspeak uses the voicemeeter input **without** AUX you can select that in any other applications that you dont want to transmit


turning it off is as easy as setting the defaukt device from VoiceMeeter AUX I/O to your desired devices, and then setting the devices in all programms to default (exept teamspeak/whatever you use to talk)
