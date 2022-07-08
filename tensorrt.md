1. TensorRT 安装与使用

nvidia-smi:  
              CUDA Version:11.6 --->  CUDAToolKit
nvcc -V:  
             Cuda compilation tools, release 11.1, V11.1.74
实际上是：11.1
cudnn:
            8.0 以上版本：cat /usr/local/cuda-11.1/include/cudnn_version.h 
            其他版本：cat /usr/local/cuda/include/cudnn.h | grep CUDNN_MAJOR -A 2
TensorRT:
            版本：
            TensorRT-7.2.3.4.Ubuntu-18.04.x86_64-gnu.cuda-11.0.cudnn8.1
            TensorRT-7.2.3.4.Ubuntu-18.04.x86_64-gnu.cuda-11.1.cudnn8.1
            上述两个版本是不一样的
            
 
            
