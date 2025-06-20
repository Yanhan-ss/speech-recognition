# speech-recognition

The rnn_lm.ipynb file shows how we can train a recurrent neural network language model.

[Spchlab](https://github.com/compi1234/spchlab) is a Repository of Jupyter Notebooks for Speech Recognition Demos, Tutorials, and Exercises. Many of the exercises of my course speech recognition reside on spchlab.

Besides rnn_lm.ipynb file, another notebook from the class: [Finetune wav2vec2.0 on Librispeech](https://colab.research.google.com/drive/1_gbLACr8XJqQSigvnkIGGacK0OoeKpX7) shows the flow of a typical Automatic Speech Reconition task, where the model is able to transcribe given speech into text. We load the wa2vec2 pretrained model from Hugging Face, and finetune it by adding a linear classification layer together with CTC loss on top of it. For demonstration purposes, we experiment on a rather small dataset, a subset of Librispeech that contains just 10min of speech.
