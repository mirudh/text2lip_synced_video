This github repository deals with 

1) The usage of pretrained bark model to synthesise audio from given text and use the same generated audio to get the lip synced video using wav2lip model.

The code for the same can be found in intergrated_code.ipynb. 

It just requires you to input text, you will get the output lipsynced video 

2) Using tortoise-tts to synthesize your own audio and use the genrated audio to get the lip synced video using wav2lip model

The code for the same can be found in tortoise-tts_wav2lip.ipynb. 

Make sure you upload at least 2 audio clips in your desired audio to generate your own voice (You can also use input_audio1.wav and input_audio2.wav uploaded in the repository). They must be a WAV file, 6-10 seconds long.
The generated audio and lip synced video is uploaded in the repository for reference.

3) Training your custom text-to-speech model

The code for the same can be found in custom_training.ipynb

