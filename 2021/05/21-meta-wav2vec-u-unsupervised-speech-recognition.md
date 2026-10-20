# wav2vec-U: unsupervised speech recognition without supervision

- **Date:** 2021-05-21
- **Who:** Facebook AI (Alexei Baevski, Wei-Ning Hsu, Alexis Conneau, Michael Auli)
- **Type:** research

Facebook AI announced wav2vec-U on 21 May 2021. It recognizes speech with no transcribed audio at all: self-supervised speech representations segment unlabeled audio, and adversarial training maps the segments to phonemes. It cut the TIMIT phoneme error rate from 26.1 to 11.3 against the best earlier unsupervised work and reached a 5.9 word error rate on LibriSpeech test-other. The method was also tested on other languages with little labeled data, such as Kyrgyz, Swahili and Tatar, and the code was released on GitHub.

## Sources
- https://ai.meta.com/blog/wav2vec-unsupervised-speech-recognition-without-supervision/
- https://arxiv.org/pdf/2105.11084v2
