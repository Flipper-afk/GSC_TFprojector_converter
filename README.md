# GSC_TFprojector_converter
Port Google Search Console (GSC) queries via Google Colab into Google's TensorFlow (TF) Projector

Table of Content:

*  1.) Download Google Search Console [GSC Queries via .csv Export](https://support.google.com/webmasters/answer/12919797?hl=en)
*  2.) Vectorize Text into High-Dimensional Space in Google Colab:
 *    - 2.1. Import Queries from .csv File
 *    - 2.2. Generate Query Embeddings via [Universal Sentence Encoder (v3)](https://www.tensorflow.org/hub/tutorials/semantic_similarity_with_tf_hub_universal_encoder)
 *    - 2.3. Export Query Embeddings as .csv File
*   3.) Import Query Embeddings into [Tensorflow Projector](https://projector.tensorflow.org/)

Read more about the [TF Embedding Projector: a tool for visualizing high dimensional data ](https://ai.googleblog.com/2016/12/open-sourcing-embedding-projector-tool.html)
