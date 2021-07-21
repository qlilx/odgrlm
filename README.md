# odgrlm
On Designing Good Representation Learning Models

This code is implementation of paper https://arxiv.org/abs/2107.05948

ABSTRACT

The goal of representation learning is different from the ultimate objective of machine learning such as decision making, it is therefore very difficult to establish clear and direct objectives for training representation learning models. It has been argued that a good representation should disentangle the underlying variation factors, yet how to translate this into training objectives remains unknown. This paper presents an attempt to establish direct training criterions and design principles for developing good representation learning models. We propose that a good representation learning model should be maximally expressive, i.e., capable of distinguishing the maximum number of input configurations. We formally define expressiveness and introduce the maximum expressiveness (MEXS) theorem of a general learning model. We propose to train a model by maximizing its expressiveness while at the same time incorporating general priors such as model smoothness. We present a conscience competitive learning algorithm which encourages the model to reach its MEXS whilst at the same time adheres to model smoothness prior. We also introduce a label consistent training (LCT) technique to boost model smoothness by encouraging it to assign consistent labels to similar samples. We present extensive experimental results to show that our method can indeed design representation learning models capable of developing representations that are as good as or better than state of the art. We also show that our technique is computationally efficient, robust against different parameter settings and can work effectively on a variety of datasets. 

REQUIREMENTS

PyTorch 1.8.0
torchvision 0.9.0
CUDA 11.0
