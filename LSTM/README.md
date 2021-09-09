#### An update to RNNs is called LSTM, long short - term memory.

In addition to the context being passed as it is in RNNs, LSTMs have an additional pipeline of contexts called `cell state`. This can pass through
the network to impact it. This helps keep context from earlier tokens relevance in later ones so issues like missing context at the end of long
sentences can be avoided.

#### Cell states can also be bidirectional. So later contexts can impact earlier ones.
