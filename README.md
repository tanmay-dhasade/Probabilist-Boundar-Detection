# Probabilistic Boundary Detection


## Requirements:

1. CUDA Toolkit + GPU drivers

2. Pytorch

3. Numpy

4. Matplotlib

5. Opencv

## Usage Guidelines:

### Phase 1:

## Algoirthm

![algo](/Phase1/Files/pb-lite-algo.png)
<p align="center">
  <img src="/Phase1/Files/pb-lite-out.png"> 
<p/>

1. Open '/Phase1/Code'.
2. Run 
```
python3 Wrapper.py
```
2. The outputs of the code will be saved in respective folders already made.

### Phase 2:

#### Training:
1. To start training model open 'Phase2/Code'
2. Run 
```
python3 Train.py
```
3. By default DenseNet model is already loaded in the python file.

#### Testing:
1. To check the confusion matrix on the test set follow the below steps.
2. To load respective model, pass the saved model path as command line argument.
E.g. To load DenseNet model, run the following command:
```
python3 Test.py --ModelPath ../Checkpoints_dense/model.ckpt
```
