The paper was turning point in deep learning research, the transformer architecture that the paper talk about used in state-of-the-art models in NLP, tasks like machine translation handled by sequence-to-sequence architecture and it is consisted of encoder and decoder.
The encoder takes the input sequence and maps into a higher dimensional space, and then the decoder turns it into an output sequence. The encoder and decoder use stacked self-attention, fully connected layers.
First step in encoder is converting inputs into input embeddings, the embedding layer in transformer produced 512-dimensional vector.
A vector containing pairs of sines and cosines for each frequency.
Self-attention may assist computers in comprehending. The results after all go through SoftMax operations. 
The number of stacked encoder units was 6 encoders every 2 together.
For the decoder, Ex: when translate English to French this is how the model works, first we feed the English sentence into the encoder and it will understand it very well, the encoder must process the entire sentences, and will produce an output which will be fees to the decoder, based to the encoder output to decode the decoder choses the word most likely the correct translation.
That what I understand from the paper after reading it and see some videos about how it works the transformer’s on the paper. 
The transformer architecture was designed with NLP tasks.
