# Google's MnasNet searches for mobile CNNs using measured phone latency

- **Date:** 2018-08-07
- **Who:** Google Brain
- **Type:** model

Google introduced MnasNet, a reinforcement learning architecture search that measures model speed directly on Pixel phones and trades it off against accuracy. The searched models were 1.5 times faster than MobileNetV2 and 2.4 times faster than NASNet at the same ImageNet accuracy. With squeeze-and-excitation, MnasNet+SE reached 76.1% top-1, matching ResNet-50 with 19 times fewer parameters, and it was also competitive on COCO detection.

## Sources
- https://research.google/blog/mnasnet-towards-automating-the-design-of-mobile-machine-learning-models/
