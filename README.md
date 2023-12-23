## Encoder/Decoder Model with HuggingFace TinyStories Corpus ##

Thee original transformer architecture released by Vaswani et al. (Attention is All You Need, 2017) utilized an encoder and a decoder. The input text is vectorized before being passed through various transformation layers and output, resulting in a word embedding. Encoders are responsible for extracting relevant information from the input text which is then passed to the decoder.

The decoder interprets a result based on the continuous representation passed from the encoder. The decoder essentially converts the input from the encoder into a different form. 

Since then, many encoder- and decoder-only transformer architectures have become available. For example, BERT is pre-trained using masked language modeling and next-sentence prediction tasks. Since the purpose of BERT (and later RoBERTa) is to perform tasks like sentence classification and question answering that require understanding the input text but not generating new text sequences, its design only incorporates an encoder. Encoder architectures are useful when tasks require only understanding. Because of this narrower focus, these models can become more efficient and specialized. GPT is a decoder-only model because it is based on the decoder part of the original Transformer architecture. Decoder models are autoregressive, in that they generate output one part at a time, using their previous outputs as input for their next steps. GPT is a decoder-only model because its focus is to generate text. Thus its architecture is tailored for these kinds of autoregressive applications. 






