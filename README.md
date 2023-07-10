# AUDIO_PITCH_CONVERTER_CREPE_intruments

Crepe is a deep learning-based system that can be used for pitch estimation from audio signals. It provides a convenient way to convert audio signals from musical instruments into corresponding pitch values. The pitch estimation is a crucial task in music analysis, transcription, and other applications involving audio processing.

It's important to note that Crepe is just one of many pitch estimation methods available. Depending on your specific needs, there may be alternative approaches or libraries that could also be suitable for your task. However, Crepe has gained popularity due to its accuracy and ease of use.

in this repo, you need audio samples in form of .wav format using which ull be converting it into a .csv where frequency,time and confidence of the corresponsing audio will be saved. this will be done using crepe

install crepe:

pip install crepe

get a csv file from wav file:

crepe ~/audio_sample.csv

