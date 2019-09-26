Chap 3. <Chap3.1-3.2>

_this is super helpful to the MP1_

The probablistic model can actually solve major problems existing in speech recognition, spelling correction/grammatical error corretion, and the machine translation, and the augmentative and alternative communication (AAC).

Language model (LM) is to assign probabilities to sentences and teh sequences of words. There are many LMs, like, n-gram, and RNN LM (Chap 9)

chain rule of probability calculation (equation 3.3)

ngram hold the core assumption that we can *approximate* the history by just the last few words.

In bigram, two words are set as one unit. namely, one word is only dependent with one previous word. [This is the Markov assumption- the probability of a word depends only on the previous word]

use relative frequency to calculate each, and then connect them with the chain rule.

What's behind the bigram LM:syntactic nature.

To avoid _underflow_, we use log prob to replace the prob itself. p1*p2*p3 = exp(logp1+logp2+logp3)









