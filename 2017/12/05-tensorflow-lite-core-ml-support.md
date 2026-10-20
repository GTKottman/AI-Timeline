# TensorFlow Lite gains Core ML support with TensorFlow-to-Core ML converter

- **Date:** 2017-12-05
- **Who:** Google TensorFlow team, working with Apple
- **Type:** software

Google announced Core ML support in TensorFlow Lite, built with Apple. A converter turns TensorFlow models into Apple's Core ML `.mlmodel` format, so iOS apps can run TensorFlow-trained networks through Apple's on-device runtime. The tool was published as the `tfcoreml` Python package (0.1.0) and the tf-coreml project on GitHub. It mattered because it gave iOS developers a supported path from TensorFlow training to on-device inference without rebuilding their models.

## Sources
- https://developers.googleblog.com/2017/12/announcing-core-ml-support.html
- https://pypi.python.org/pypi/tfcoreml/0.1.0
