Lets understand it via Gradient Descent!
We know in GD:
Batch Gradient Descent- Batch Size = Size of Training Set.
Stochastic Gradient Descent. - Batch Size = 1.
Mini-Batch Gradient Descent. - 1 < Batch Size < Size of Training Set.

#EPOCHs: It is the number of times the whole training dataset is passed through the model. 
So in one epoch every data point has passed the model once.

#BATCH: An epoch can have number of batches. And one batch epoch is called Batch GD, 
so in this case whole dataset is passed through the model at one go and the optimization also is allowed only once. 
So basically a batch size is the number of data point after the model gets updated.

#ITERATIONS: Its the number of batches required to complete one epoch. 
lets have an example, if we have 3000 datapoints and batch size is 200 then we have 1000/200 = 5 iterations per epoch and model updation will be happening every iteration 
i.e after every batch in an epoch.
