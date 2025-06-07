# CHAt_BOT_SEQ2SEQ
This is a chatbot trained by seq2seq and reinforcement learning.

# seq2seq
Seq2seq is a classical model for structured learning, its input and output are both sequence

The vanilla seq2seq model is described in a NIPS '14 paper Sequence to Sequence Learning with Neural Networks, the encoder and the decoder are seperated

The seq2seq model in this repository is constructed with 2 LSTMs, similar to the one described in an ICCV '15 paper Sequence to Sequence -- Video to Text, the encoder and the decoder share same weights

# RL

After training chatbot with enough epochs, I use a RL technique called policy gradient to further improve the chatbot

By doing this, the chatbot can generate more interesting response with regard to the reward function

My reward function is similar to the one described in an EMNLP '16 paper Deep Reinforcement Learning for Dialogue Generation
Let me show you some chatbot's results:



