# OpenCV_Test
**The project has two main effect:**
- OpenCV's usage
- fbc_cv library

**The project support platform: windows7/10 64 bits. It can be directly build with VS2013 in windows7/10 64bits.**

**OpenCV's version: 3.1**
- close support for OpenCL/CUDA/SIMD/TBB/OpenMP when build with CMake
- modify sources/modules/core/include/opencv2/core/cvdef.h, for example: #define CV_SSE2 0
- insure that all algorithms are implemented with c++

# fbc_cv
- it is an open source image process library
- most of the algorithms come from OpenCV3.1
- it has a template class Mat_ replace of OpenCV's Mat class: src/fbc_cv/include/core/mat.hpp
- interface names are consistent with OpenCV3.1
- each algorithm's result is same with OpenCV3.1
- the codes are written in C++ without dependence on any 3rd-party libraries

**The algorithms have been implemented include:**
- resize
- cvtColor
- merge/split
- remap
- warpAffine
- rotate
- warpPerspective
- dilate
- erode
- morphologyEx
- threshold
- transpose
- flip
- dft/idft

**Screenshot:**  
![](https://github.com/fengbingchun/OpenCV_Test/blob/master/prj/x86_x64_vc12/Screenshot.png)

**Blog:** [fengbingchun](http://blog.csdn.net/fengbingchun/article/category/721609)

**Licence: uses the same licence as OpenCV3.1**
