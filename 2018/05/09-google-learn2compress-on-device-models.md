# Google's Learn2Compress shrinks pretrained models for phones and IoT devices

- **Date:** 2018-05-09
- **Who:** Google AI
- **Type:** software

Google introduced Learn2Compress, a technology that turns large pretrained TensorFlow models into smaller, faster models for mobile and IoT devices. It uses pruning, quantization and joint training with distillation to limit the accuracy loss. On ImageNet the post reported a model 22 times smaller than the Inception v3 baseline, with a 4.6 to 7% accuracy drop. It made on-device deployment of custom models practical.

## Sources
- https://research.google/blog/custom-on-device-ml-models-with-learn2compress/
