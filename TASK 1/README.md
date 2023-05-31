I was able to build CNN on CIFAR 100 dataset using softmax and gumbel-softmax activation functions successfully 

# The metrics of CNN model using standard softmax activation function :- 

Confusion matrix: 
                  
                  [[83 0 0 ... 0 0 0] 
                  
                   [ 0 82 0 ... 0 0 0] 
                   
                   [ 0 0 44 ... 0 4 0] 
                   
                   ... 
                   
                   [ 0 0 0 ... 64 0 0] 
                   
                   [ 0 1 4 ... 0 34 0] 
                   
                   [ 0 0 0 ... 0 0 67]] 
                   
F1 score: 0.593415 

Accuracy score: 0.593100 

Precision score : 0.600344 

Recall score : 0.593100


# The metrics of CNN model using gumbel-softmax activation function :-

Confusion matrix: 

                  [[87 0 1 ... 0 0 0] 

                  [ 0 75 0 ... 0 0 2] 
                  
                  [ 2 0 52 ... 0 4 0] 
                  
                  ... 
                  
                  [ 0 0 0 ... 50 0 0] 
                  
                  [ 0 1 8 ... 0 31 0] 
                  
                  [ 0 0 0 ... 0 0 54]] 
                  
F1 score: 0.553175 

Accuracy score: 0.554900 

Precision score : 0.558441 

Recall score : 0.554900


I was unable to implement the Adaptive Softmax function properly but I have shared the code whatever I was able to implement!
