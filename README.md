# W2V-E2E-Language-diarization

The following repository contains code to the papaer 'End to End Spoken Language Diarization with Wav2vec Embeddings' which has been accepted in Interspeech 2023.

# Overview

Most of the Code-switched language suffers from primary language biasness. This id due to the unavailibility of of sufficient secondary language data. Our approach uses the pretrained features from a W2V model instead of using x-vector initially, which provides a performance improvement of around 30.7% in terms of Jaccard error rate (JER) over the baseline x-vector-based E2E (X-E2E) framework. The performance is furthur improved by using finetuned features from the W2V model and and modifying the temporal aggregation strategy from statistical pooling to attention pooling. The Final performance achieved in terms of JER is 22.5, which provides a relative improvement of 38.8% and 62.6% over the standalone W2V fine-tuned and the baseline X-E2E framework, respectively. 
