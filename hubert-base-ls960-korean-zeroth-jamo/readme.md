---
language: ko
datasets:
- kresnik/zeroth_korean
tags:
- speech
- audio
- automatic-speech-recognition
license: apache-2.0
model-index:
- name: 'hubert base Korean'
  results: 
    - task:
        name: Automatic Speech Recognition
        type: automatic-speech-recognition
      dataset:
        name: Zeroth Korean
        type: kresnik/zeroth_korean
        args: clean
      metrics:
        - name: Test WER
          type: wer
          value: 30
        - name: Test CER
          type: cer
          value: 
---


https://github.com/Rosicast/huggingface/blob/master/hubert-base-ls960-korean-zeroth-jamo/hubert_base_inference.ipynb