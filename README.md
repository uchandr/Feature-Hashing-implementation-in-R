Purpose of the project is to compare the model built using feature hashing w.r.t to the traditional machine learning approach

The dataset provided has all categorical variables with high cardinality

Feature hashing technique(aka Hashing trick) was implemented to create a model matrix with feature hashing
Feature hashing is a method to transform features to vector. Without looking up the indices in an associative array, 
it applies a hash function to the features and uses their hash values as indices directly.

An advantage is that it works with address locations instead of actual data, this allows it to process data only when needed. So, the first feature found is really a column of data containing only one level (one value), when it encounters a different value, then it becomes a feature with 2 levels, and so on. It also requires no pre-processing of factor data; you just feed it your factor in its raw state. 
This approach takes a lot less memory than a fully scanned and processed data set.
