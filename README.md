# Silero Transcribe

> Silero models are a set of pre-trained speech-to-text, text-to-speech and text-enhancement models, for more you can check [snakers4/silero-models 
](https://github.com/snakers4/silero-models)


## Intent

Inspired by one of the teams in the final project demo in [CS 329S: Machine Learning Systems Design](https://stanford-cs329s.github.io/)


## Experiment

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Zhenye-Na/silero-transcribe/blob/main/silero_transcribe.ipynb)

I have used [this](https://www.youtube.com/watch?v=iaxqTVNHFB0) video on YouTube to generate subtitles for it, by simply following along the silero colab [examples](https://colab.research.google.com/github/snakers4/silero-models/blob/master/examples.ipynb#scrollTo=8r3DW7IgkJil) and a small script to transform the model output to a `srt` file/

The following is the audio that got extracted.

[](https://user-images.githubusercontent.com/32248549/158008526-6feb8602-8073-4d72-a203-57975f7e32d0.mp4)

The following is the `srt` file format I generated.

```
1
0:00:01.320000 --> 0:00:05.080000
hi everybody i've spoken and a lot of events over the years

2
0:00:05.560000 --> 0:00:08.920000
including some with pretty impressive lineup but i've

3
0:00:09 --> 0:00:13.400000
never been part of the same program as pope francis black

4
0:00:13.560000 --> 0:00:19
pink and spunge bob square parenants i am a little star truck

5
0:00:19.640000 --> 0:00:23.910000
but the fact that all of them are part of this along with a lot
```

