---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default 
---

![xiaowang(王霄)]({{ site.url }}/wangxiao.jpg){:class="img-responsive"}


I am a second-year graduate student in [State Key Laboratory of Computer Architecture](http://www.carch.ac.cn/), [Institute of Computing Technology, Chinese Academy of Sciences (SKL, ICT, CAS)](http://www.ict.cas.cn/). I am supervised by Prof. [Yunquan Zhang](http://sourcedb.ict.cas.cn/cn/jssrck/201308/t20130822_3917018.html) on the high performance computing including performance tuning, SIMD optimization, GPGPU.

# Education
- 2017.9-Now, Institute of Computing Technology, Chinese Academy of Sciences, Master., High Performance Computing, Supervisor: Prof. [Yunquan Zhang](http://sourcedb.ict.cas.cn/cn/jssrck/201308/t20130822_3917018.html).

- 2013.9-2017.7, Yunnan University, B.Eng, Computer Science(Top 5%). 

# Research Projects

- RealFFT Library, High performance implementation of 1D-3D float/double Real FFT on both ARMv8 and X86-64 CPU.                     Core Developer

   - Implement stockham butterfly-network for even-size real input data, including 11 real FFT kinds.

   - Optimize computation in NEON and AVX on ARMv8 and X86 respectively.

   - Faster than [FFTW](http://www.fftw.org/) on ARMv8 platform around 34%~53% for 1D transforms, 10%~41% for 2D transforms, and achieve a nearly matchable performance than [MKL](https://software.intel.com/en-us/mkl/features/fft) for some kinds.


- A high-performance IPP library on ARMv8 architecture.                                                                             Core Developer

   - Implement performance primitives on ARMv8 corresponding to Intel IPP counterpart, such as median filter, max, min, e^x, ln(x).

   - Optimize these operations with NEON intrinsics on ARMv8.

# Internship

- Amazon AWS AI Lab(ShangHai) (2019.06~2019.08)                                 Software Developer Intern

   - Develop numpy-compatible operators for MXNet.

- PerfxLab(Startup in Beijing) (2019.03~2019.06)                                Core Developer

   - A high-performance Gaussian Filter on AMD GPU based on OpenCL.

   - Implement column-row seperatable gaussian filter based on OpenCL.

   - Tune performance specifically for AMD GPU (GCN Architecture).

   - Faster than its counterpart of OpenCV around 21%-33%, especially when filter size is larger than 5.


# Publications

- [Implementation and Optimization of Multi-dimensional Real FFT on ARMv8 Platform](http://www.escience.cn/system/download/103329). **Wang Xiao** and Jia Haipeng and Li Zhihao and Zhang Yunquan. International Conference on Algorithms and Architectures for Parallel Processing: 2018 ,338-353. Guangzhou, China. (ICA3PP18, CCF C; EI).

- [Efficient parallel optimizations of a high-performance SIFT on GPUs](http://www.escience.cn/system/download/102821). Zhihao Li and Haipeng Jia and Yunquan Zhang and Shice Liu and Shigang Lia and **Xiao Wang** et al. Journal of Parallel and Distributed Computing: 2019 ,124 ,78 - 91. (JPDC, CCF B; SCI, Impact Factor:1.815).

- [AutoFFT: A Template-Based FFT Codes Auto-Generation Framework for ARM and X86 CPUs](). Zhihao Li, Haipeng Jia*, Yunquan Zhang, Tun Chen, Liang Yuan, Luning Cao, **Xiao Wang**. The International Conference for High Performance Computing, Networking, Storage, and Analysis. November 17–22, 2019, Denver, CO, USA. (SC19, CCF A).

- [MVUC: An Interactive System for Mining and Visualizing Urban Co-locations](https://link.springer.com/content/pdf/bbm%3A978-3-319-39958-4%2F1.pdf). **Xiao Wang**, Hongmei Chen*, Qing Xiao. Conference on Web-Age Information Management 2016, 524-526. Nanchang, China. (WAIM16; Demo Paper, CCF C; EI).

# Awards

- 2019 Merit Students Awards of University of Chinese Academy of Sciences.

- 2017 Outstanding Undergraduate Students Awards of Yunnan province(Top 5%).

- 2016 The CCF Outstanding Undergraduate Award.(Select 100 undergraduate students every year from all universities in China)

- 2015 Second Prize in Contemporary Undergraduate Mathematical Contest in Modeling. 

# Skills

- Programming Language: proficient in c, SIMD(Neon/AVX), skilled at OpenCL/c++. 
- Development Tools: proficient in VIM, CMAKE, Git, gcc, g++, average at Google GTEST, Makefile. 
- English Level: Toefl 102.

# Contact

- Email Address: wangxiao17s@ict.ac.cn or lmzxiao@gmail.com

- Address: No.6 Zhong Guan Cun Ke Xue Yuan South Road, Haidian District, Beijing, China <br/>

# Resume
[Resume]({{ site.url }}./wangxiao_cv_long.pdf)
