# CHAt_BOT_SEQ2SEQ
This is a chatbot trained by seq2seq and reinforcement learning.

seq2seq
Seq2seq is a classical model for structured learning, its input and output are both sequence

The vanilla seq2seq model is described in a NIPS '14 paper Sequence to Sequence Learning with Neural Networks, the encoder and the decoder are seperated

The seq2seq model in this repository is constructed with 2 LSTMs, similar to the one described in an ICCV '15 paper Sequence to Sequence -- Video to Text, the encoder and the decoder share same weights

RL
After training chatbot with enough epochs, I use a RL technique called policy gradient to further improve the chatbot

By doing this, the chatbot can generate more interesting response with regard to the reward function

My reward function is similar to the one described in an EMNLP '16 paper Deep Reinforcement Learning for Dialogue Generation
Let me show you some chatbot's results:

Result 1 (A & B are both a trained chatbot)
A: Can you do me a favor?
B: Anything.
A: I want you to bend a father.
B: Of course.
A: I'm so sorry I didn't mean to be rude but.
B: Don't get it at least it's about as much as I can.
Result 2 (A & B are both a trained chatbot)
A: I didn't do it! I haven't got a gun!
B: You liar. You still want to get your money back.
A: Something wrong with the truth.
B: I don't want any money just a little I can't take just out of this.
A: What's wrong.
B: Listen to me. I'm scared now.
A: Ah you'll need all the money I need your help.
Result 3 (A & B are both a trained chatbot)
A: I forgot to get the Coca-Cola.
B: I got something stuck in the head.
A: It's all right I guess it's pretty common in the lot of shit.
B: I mean we've been all this together since the kid.
A: All the more reason.
B: It's not him it's his fault and he's blind because of god.
A: And is a strange story.
you can find more results from chatbot in this directory

neural networks' configs of those results are described in the filename

