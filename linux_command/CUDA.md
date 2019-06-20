# 查询CUDA版本号：
## cuda 版本 
（1）`nvcc --version`
（2）`cat /usr/local/cuda/version.txt`
## cudnn 版本 
`cat /usr/local/cuda/include/cudnn.h | grep CUDNN_MAJOR -A 2