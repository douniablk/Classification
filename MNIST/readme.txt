1.why we should shuffle the data?
some learning algorithms are sensitive to the order of the training  instances, 
and they perform poorly if they get many similar instances in a row. 
Shuffling the dataset ensures that this won’t happen
NB: Shuffling may be a bad idea in some contexts for ex if we're working on time series data (such as  stock market prices or weather conditions).


2.what skewed dataset mean ?
the data pints are not semmytrical when a class is more frequent than the other this can affect the performance of a ML models 
NB:accuracy is not the preferred performance measure for classifiers especially when we are dealing with 
a skewed dataset 



