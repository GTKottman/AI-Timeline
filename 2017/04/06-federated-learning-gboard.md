# Federated Learning: training on phones without centralizing data

- **Date:** 2017-04-06
- **Who:** Google Research (blog post); Gboard on Android as the named application
- **Type:** research

Google Research described Federated Learning, in which phones jointly train a shared prediction model while the training data stays on each device. Each device downloads the current model, improves it on local data and sends back only a small update, which the cloud averages with updates from many users. The post introduced Federated Averaging, which needs far less communication than a naive approach, and a Secure Aggregation protocol that stops the server seeing any single phone's update. It was tested on Gboard, Google's Android keyboard, for query suggestions.

## Sources
- https://research.google/blog/federated-learning-collaborative-machine-learning-without-centralized-training-data/
