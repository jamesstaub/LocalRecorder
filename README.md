# Local Recorder
*very much work in progress*

## project goals
1. Create a progressive web app for recording audio memos with text and geolocation.

2. Use this app to create an open dataset of audio recordings with geolocations and other meta data.  

3. Experiment with Polymer, learn more about progressive web apps and web audio encoding.  

-----

## to do:

- Complete integration of Recordmp3js into the note app, allowing user to record an audio file through the device microphone, encode it to mp3, and upload it to firebase data store.  

- refine interface to display waveform and allow user to edit/delete audio files on per-note basis. implement a simple audio cropping interface.

- add suggested + custom tags for users to classify their audio recordings

- create separate list views for user's own notes and other users notes in the database (initial assumption is that all notes will be public)

- create a map interface to display audio notes at their given locations. (there will likely be separate app for analyzing audio and visualizing the notes on a map)

- Use Meyda to perform audio descriptor analysis on audio files, use this analysis data to visualize notes by timbre (MFCC)




The structure of the note app is based heavily on the polymer note app tutorial from google code labs.
