# Purpose Of This Document

We would like to thank you for agreeing to be interviewed for one of our podcasts. In preparation of your appearance on one of our shows, we would like to share this document with you as it provides answers to some of the frequent questions guests ask about being interviewed for one of the [RJJ](https://rjj-software.co.uk) produced podcasts. Hopefully, this document will provide answers to any questions that you have and provide a little insight into the process of being interviewed for the show.

If you still have questions, please feel free to contact us and ask directly. We will likely ask for permission to include a version of your questions in the next version of this document.

Our thanks go out to [Love Sudo Nimh](https://twitter.com/joseyhowarth) for helping with the formatting and general language used in this document.

## Generic Questions

### Do I Need Any Specific Equipment?

You will need:

- a microphone
- a pair of headphones, earphones, or a form of audio monitor
- a PC, laptop, or similar
- a web browser

We usually conduct interviews using the [SquadCast software-as-a-service platform](https://squadcast.fm/). We have found this to be more stable than using other VoIP methods (i.e. Skype), as SquadCast records locally and streams to the cloud. It also keeps each vocal track separately, that way our editing team can tweak each audio track (i.e. remove any background noise) from one track without affecting the others. It also has no software dependencies other than a modern web browser = please check their [How to be a Guest](https://squadcast.fm/guest/) page for more details.

### SquadCast's Permissions

SquadCast uses your browser to record the episode. As such, it needs to get you permission to use the microphone. It will also ask for access to your camera (if you have one) and your GPS. You don’t have to agree to either of these if you don’t want to - they’re not required to make SquadCast work, and won’t be used for the recording in any way.

If you give permission for the camera to be used, everyone in the recording session will be able to see you. If you decline that, but give permission for your location to be used, then everyone will see a map, with your rough location on it - there will be no pin, but it will be correct at the town level. An example can be seen below:

![An example of the map shown when GPS is permitted](.\images\gps-permitted.png)

If you decline both, then everyone will be presented with a world map which is not zoomed in on any location at all - focussing instead on the equator.

We will be enabling our cameras, that’s largely because we like to use the camera to get visual cues as to who wants to talk about something. But this is not required at all.

### Advice for the Best Sounding Recording

Whilst we will work to the best of our abilities when editing the recording, we ask that you take a few steps to ensure that the recording is of the highest quality possible:

- Ensure that you are in a quiet area
- Ensure that family members and/or roommates know that you are recording and ask them to not interrupt you
- Ensure that all un-necessary applications are closed or halted
- Ensure that all un-necessary browser tabs are closed
- If possible, connect your microphone and camera (if using one), then reboot your computer
  - This is advice given to us by SquadCast employees. The rationale being that some OSs can have issues addressing microphones after booting.
- Please ensure that mobile/cell phones, tablets, and ancillary devices are set to "do not disturb"
- Please ensure that you are not connected to a VPN
  - SquadCast explicitly state that they do not support VPN usage
  - If you do use a VPN, then the recording may not complete correctly, rendering the discussion useless
- Please check your internet connectivity beforehand
  - We recommend using [fast.com](https://fast.com) as provided by Netflix
- We may ask you to perform a "double ender":
  - This is where we will ask you to record your own audio at your end and send it over after the fact
  - This can be facilitated by installing [Audacity](https://www.audacityteam.org/) or a similar audio recording application
  - We only require your audio, so the use of [Audio Hijack](https://rogueamoeba.com/audiohijack/) (and similar applications) is not recommended
  - Once completed, we will require you to send us the recorded audio encoded in FLAC format
    - This can be done by Exporting as FLAC from within Audacity
    - Or installing [ffmpeg](https://www.ffmpeg.org/) and running the following command (assuming that you have already exported as a wave file): `ffmpeg -i input_file.wav exported_flac.flac`
- If possible, please connect to your network via ethernet rather than WiFi
  - This can increase your available bandwidth and data transfer speed, potentially increasing the fidelity of the audio recorded

### How Will You Arrange The Interview?

Typically, We will arrange the interview date and time via email.

We tend to favour finding a date and time which is convenient for the person(s) we are interviewing. As such, it may take a few rounds of emailing in order to pick the most convenient time.

Once the date and time have been confirmed, We will arrange a SquadCast recording session and send a notification to each person who will be interviewed. The notification from SquadCast will be in the form of an email, and will contain a link directly to the recording session.

We will also send over a podcast planning document. This document will contain a link to the SquadCast recording session, a link to this document, and a summary of the questions, topics, and points that we are aiming to cover in the session. Please see the [Podcast Planning Document](#podcast-planning-document) section for more details.

### How Long Will The Interview Last?

We usually ask that guests block out 90-120 minutes of their schedule for the interview, however most interviews will take less than 90 minutes.

The reason that we ask guests to block out that much time is to ensure that we have time for a sound check and a light chat at the beginning of the session, along with a conversation about when we are planning to release the episode at the end of the session.

The entire session should take no longer than around 50 minutes of your time, and the recorded portion of that should be around 40-45 minutes long.

You are free to take as much time as you may need in order to answer a question. Similarly, if you find that you would like to "start over" with your answer to a question, you need only ask.

### Will I Receive a Copy Of The Interview Before It Goes Live?

We will contact you once editing is completed and will offer a pre-live version of the episode. This is so that you can go through it and let us know of any further edits you would like me to make (i.e. remove the long "um" at 39 minutes).

As our release schedule is rather agile in its nature, We would need notes back from you as soon as possible. The lead time in releasing to the public RSS feeds is usually a few days but can be up to a week, as such we will need at least a few days notice for any requested edits.

### Podcast Planning Document

In advance of the recording session, we will send over a document which will outline the episode we wish to record with you. This document will contain:

- A link to the SquadCast recording session
- A link to this document
- A collection of questions, topics, and points that we would like to discuss
- A request for a profile (if required)

This document is collaborative in nature and we ask you to feel free to edit the list of questions, topics, and points, along with anything else in the document ahead of recording. We will use this document whilst recording the episode, as an aid to memory.

## Show Specfic Questions

For show specific questions, please see the following list:

- [The .NET Core Podcast FAQ](show-specifics\dotnetcore.md)
- [The Waffling Taylors Podcast FAQ](show-specifics\wafflingtaylors.md)
