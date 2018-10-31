Palaver-speech-recognition
=========================
Recently, there has been a push to get a high-quality native Linux speech recognition engine developed. As a result, numerous projects dedicated to creating Linux speech recognition solutions were established, such as Mycroft. Mycroft is similar to Microsoft's Cortana, but open source.
Crowdsourcing of speech samples
It is essential to compile a speech corpus to produce acoustic models for speech recognition projects. VoxForge is a free speech corpus and acoustic models repository that was built with the aim of collect transcribed speech to be used in speech recognition projects. VoxForge accepts crowdsourced speech samples and corrections of recognized speech sequences. It is licensed under the GPL. 



The first step is to begin recording an audio stream on a Linux machine. The user has two main processing options:

    (DSR) Discrete Speech Recognition - process the voice recognition entirely on local machine. This refers to self-contained systems in which all aspects of SR (Speech Recognition) are performed entirely within the user's computer. This is becoming critical for protection of IP (Intellectual Property) and avoiding unwanted surveillance (2018).
    (Remote) Server-based SR which transmits the speech file to a remote server for converting the audio file into a text string. Due to recent Cloud storage schemes and data mining, this method more easily allows surveillance, theft of IP and introduction of malware.

FYI, The second option (remote) was previously used on smart phones as they did not possess sufficient performance, disk space or RAM to process speech recognition on-board the phone.These limitations have largely been overcome although server-based SR on mobile devices remains universal. 
Speech Recognition in Browser

Discrete Speech Recognition can be performed within a web browser and works well with supported browsers. Remote SR does not require installation of software on the desktop computer or mobile device as it is primarily a server-based system with the inherent security issues noted above.

    (Remote): https://dictation.io (use Chromium/Chrome) The dictation service records an audio track of the user via the web browser. In turn, dictation.io uses the Google API for speech recognition. Within Google Docs, Google voice typing works within the Chrome browser, regardless of operating system as it is a server-based system.

    (DSR): There are solutions that work on the client only, without sending data to servers
Open speech recognition for Linux

NOTE: GOOGLE has since closed their speech recognition api. Because of this, another API would have to be used to allow palaver to work.
