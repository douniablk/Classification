1.why we should shuffle the data?
some learning algorithms are sensitive to the order of the training  instances, 
and they perform poorly if they get many similar instances in a row. 
Shuffling the dataset ensures that this won’t happen
NB: Shuffling may be a bad idea in some contexts for ex if we're working on time series data (such as  stock market prices or weather conditions).


2.what skewed dataset mean ?
the data points are not semmytrical when a class is more frequent than the other this can affect the performance of a ML models 
NB:accuracy is not the preferred performance measure for classifiers especially when we are dealing with 
a skewed dataset 

3. Measuring performance :
precision/recall trade-off
Let me explain to you in an easy way:
Imagine that you're a security guard.
You have to make a decision about who you let into a building based on face recognition.
Each person has a score between [0,1]. The decision threshold (th) determines who is allowed in.

If th=0.5, anyone with a score above 0.5 is allowed.
If th=0.7, anyone with a score above 0.7 is allowed.

Precision & recall vs decision threshold:
If we set th=0.7, we are more selective, so precision increases because we're letting in the most confident matches. However, we may miss some authorized people, so recall will decrease.
If we set th=0.3, most authorized people are allowed in, so recall increases. But we are letting more unauthorized people in, so precision decreases.
If someone says, “Let’s reach 99% precision,” you should ask, “At  what recall?”



