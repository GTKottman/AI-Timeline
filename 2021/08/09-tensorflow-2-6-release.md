# TensorFlow 2.6.0 released, Keras split into its own package

- **Date:** 2021-08-09
- **Who:** Google (TensorFlow team)
- **Type:** software

TensorFlow 2.6.0 was released as a stability release. Its headline change was moving Keras out of the main repository into its own pip package and GitHub repository (keras-team/keras), while tf.keras keeps the same API surface. The release also removed or changed several APIs; Model.to_yaml() and model_from_yaml now raise a RuntimeError because they could be abused for arbitrary code execution. The GitHub release is dated August 9, 2021.

## Sources
- https://github.com/tensorflow/tensorflow/releases/tag/v2.6.0
