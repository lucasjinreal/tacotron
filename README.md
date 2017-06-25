#  Tacotron

> this work original implement by [kyubyong](https://www.github.com/kyubyong/tacotron), I changed it into my version. Thanks for the original author. And of course this work is based on [Google Original Paper](https://arxiv.org/abs/1703.10135).


# Requirements

* Python3
* Tensorflow 1.2 (the newest version)
* Python Package: librosa, tqdm

# Train

To start to train tacotron, should download audio file from [here](https://dl.dropboxusercontent.com/u/42868014/WEB.zip), and the accordingly text file from [here](https://dl.dropboxusercontent.com/u/42868014/text.csv). These two file can be changed into your own training data. For other language, only prepared the audio data and the text data, the model can be trained without even change the python codes.

# Predict

To using model to convert text to audio, just run the `eval.py`, and give your text, you will get some examples of audios.

# Contact and Research

If you want to train an TTS model for Chinese, you can add me wechat, we are working on that: `jintianiloveu`.

# Copyright

This Code OpenSource Under Apache 2.0 License.