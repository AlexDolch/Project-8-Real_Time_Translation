# Project-8-Real_Time_Translation

-----------

Our final project we did @WBS Coding School; we had to decide what we want to do and went for a real-time translator,
which was an ambitious, yet very exciting thing to do!
We narrowed it down to smaller steps, aka the Speech-To-Text(STT), the Translation and the Text-To-Speech(TTS) part;

STT: We used the vosk library there, which came in super handy since it provided us with a lot of different models to play around with,
covering over 20 languages that we can use as input and open source with the models trained in an academical background. :)

Translation: We decided for a simple API call to google here, since its one of the best translators available and we didnt want to risk
to have too much computing power needed. The go-to to run on local systems would be hugging face/transformers here, I suppose.

TTS: pyttsx3 was our way to go here. This was the part we explored the most possibilities and found this library as the one easiest to get running.
With it´s way to modify the speed of the output, it easily let´s us have a constant flow of speech coming out - 
instead of pausing in between the processed chunks of audio.

a short showcase and explanation can be seen here: 
https://www.youtube.com/watch?v=GcQiTYTKC8s&t=33s&ab_channel=alexd

-----------
