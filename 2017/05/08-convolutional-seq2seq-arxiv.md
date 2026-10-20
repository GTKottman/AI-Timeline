# Convolutional sequence-to-sequence learning (arXiv)

- **Date:** 2017-05-08
- **Who:** Jonas Gehring, Michael Auli, David Grangier, Denis Yarats, Yann N. Dauphin (Facebook AI Research)
- **Type:** paper

The paper "Convolutional Sequence to Sequence Learning" (arXiv 1705.03122) replaced the recurrent encoder-decoder used in machine translation with a fully convolutional one, with gated linear units and attention in each decoder layer. Because nothing is recurrent, training runs in parallel across positions; the authors reported higher WMT'14 translation accuracy than deep LSTM systems and roughly ten times faster decoding. The code was released in the fairseq toolkit, and the design influenced later fully parallel sequence models.

## Sources
- https://arxiv.org/abs/1705.03122
- https://arxiv.org/pdf/1705.03122v2
