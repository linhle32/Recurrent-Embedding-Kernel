# Recurrent embedding kernel

### Main libraries:
- Python 2.7
- theano
- numpy
- matplotlib
- pandas

#### Update 01-10-2019: my paper has been published at https://ieeexplore.ieee.org/abstract/document/8606647

***I have not had times to package this model into a class. This will be done soon.

This is the sample code for my model Recurrent Embedding Kernel (REK). Deep recurrent neural networks, such as Long Short-Term Memory, typically outperform statistical time series models and traditional machine learning approaches with their mechanisms of learning to vectorize historical information. However, encoding entire history into a vector may unavoidably causes information loss regardless of memory learning and updating mechanisms, especially for those tasks where decisions need to be made on the current time point and similar historical time points are of great references to the decision making. Instead, REK can learn to make optimal decisions by referring to the entire history instead of just current memory vectors.

### The architecture of REK is as follows

![image](https://user-images.githubusercontent.com/5643444/231943140-1b94c997-60cd-4b6e-b987-d2166074e382.png)

### The training process of REK is as follows

![image](https://user-images.githubusercontent.com/5643444/231943176-94539718-a41f-4801-8dde-4d51fec425cf.png)

