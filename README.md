# gtuner
🎸🎸

# description 🖊️
A simple guitar tuning application built using flutter with support for 
- Android
- iOS

# UI 🎨
The app's UI is currently simple with flutter's dark mode theme being used
as the app's main color together with shades of amber, white, green and red.
The tuner's UI can be improved in future to show a guitar image that auto picks the strings
based on tuning. Other UI aspects can also be improved but for now it is good enough.

Not the best designer but i try 😂. Maybe I can collab with a designer to improve it 

# functionality ✨
- Tuner : 12 different tunings
- Metronome : tempo between 30 and 240 BPM
- Chord Library : Chords shapes of 9 different chord types

# Future Features To add 📔
- Songs to play along with sync

# Dependencies 
This app makes use of some important packages that power the tuning, chord library and metronome functionalities:

1. Tuning
- flutter_audio_capture to record sound/audio 
- pitchupdart and pitch_detector_dart to detect the pitch of the recorded sound and check whether it is in tune

2. Chord Library
- carousel_slider provides a way to slide between the chord library images horizontally

3. Metronome
- flutter_sequencer package facilitates load the metronome audio sample, setting the tempo (with some calibration first) and play/loop the sample at the tempo speed upto a certain number of beats

# Links to these helpful packages:
pitchupdart - https://pub.dev/packages/pitchupdart
pitch_detector_dart - https://pub.dev/packages/pitch_detector_dart
flutter_audio_capture - https://pub.dev/packages/flutter_audio_capture
carousel_slider - https://pub.dev/packages/carousel_slider
flutter_sequencer - https://pub.dev/packages/flutter_sequencer


This project help me learn a lot more about flutter. If you find this helpful feel 
free to contact me (deni.tomno@gmail.com) to collaborate on this or other projects





