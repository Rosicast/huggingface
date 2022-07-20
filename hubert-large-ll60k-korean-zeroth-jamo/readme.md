---
language: ko
datasets:
- kresnik/zeroth_korean
tags:
- speech
- audio
- Automatic Speech Recognition
- automatic-speech-recognition
- hubert
- hubert-base
license: apache-2.0

---


[Google colab notebook](https://github.com/Rosicast/huggingface/blob/master/hubert-large-ll60k-korean-zeroth-jamo/hubert_large_inference.ipynb)

Declaimer
- This model is on a training process.
- The performance of the model will be posted after train.
- Since this model is trained on phoneme - such as ㄱ,ㄴ,ㄷ,ㅏ,ㅣ,ㅜ, etc -, unlike other models trained on grapheme - such as 가,나,다, etc-, it would less perform on small size dataset such as this zeroth-Korean dataset (about 50 hours). However, phoneme-based models would perform better on large datasets(over 100 hours with data argument) (이문학 and 장준혁,2019).
- There could be a comparison between grapheme and phoneme-based models
- You would load your sound file through python libraries such as touchaudio, soundfile, and librosa. 

ref

이문학, & 장준혁. (2019). 문자소 기반의 한국어 음성인식. 한국음향학회지 제, 38(5), 601-606.

see more detail information about model on the offical [page](https://huggingface.co/facebook/hubert-large-ll60k)