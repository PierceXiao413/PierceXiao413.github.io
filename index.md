---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default 
---

![xiaowang(王霄)]({{ site.url }}./IMG_2345.JPG){:class="img-responsive"}

Hello! I am currently a full-time software engineer in [MaxCompute previous called ODPS](https://www.alibabacloud.com/product/maxcompute), [Alibaba's](https://my.alibabacloud.com/?utm_key=se_1007714444&utm_content=se_1007714444&gclid=EAIaIQobChMI4tKox43i-QIVEZhmAh02nwv1EAAYASAAEgIzbvD_BwE) large-scale, distributed computing and storage platform. Currently, I am busy on building and optimizing a high-performance SQL execution engine for [MaxCompute-SQL](https://www.alibabacloud.com/help/en/maxcompute/latest/overview-of-maxcompute-sql). 

Before that, I achieve my master's degree from [State Key Laboratory of Computer Architecture](http://www.carch.ac.cn/), [Institute of Computing Technology, Chinese Academy of Sciences (SKL, ICT, CAS)](http://www.ict.cas.cn/) under the supervision of Prof.[Yunquan Zhang](https://scholar.google.com/citations?user=Cxg_yNoAAAAJ&hl=zh-CN). I obtain my B.E. in [Yunnan University](http://www.ynu.edu.cn/), At that time, I was extensively involved in data mining and virtual machine migration projects.

I am interested in high-performance computing (Performance tuning and modeling, SIMD, GPGPU, GEMM, FFT) and building large-scale high-performance distributed computing systems.

# Education 
- **2017.9-2020.7**, Institute of Computing Technology, Chinese Academy of Sciences, Master, High-Performance Computing, 
- **2013.9-2017.7**, Yunnan University, B.Eng, Computer Science(3/121).

# Industry Experience
- Full-time Software engineer at [MaxCompute, Alibaba Cloud](https://my.alibabacloud.com/?utm_key=se_1007714444&utm_content=se_1007714444&gclid=EAIaIQobChMI4tKox43i-QIVEZhmAh02nwv1EAAYASAAEgIzbvD_BwE)
   - Investigate other OLAP sys(Clickhouse) & Manage releasing procedures and quality of one sprint covering different releasing regions and core users **July.2020-July.2021**.
   - Design adaptive distributed aggregation algorithms which are interchangable between hash-based and sort-based algorithms during runtime depending on data statistical characteristics **Aug.2021-Dec.2021**. 
   - Refactorize high-performance vectorization aggregation for 30 kinds of aggregate functions **Jan.2022-Mar.2022**.
   - Design and implement hash-based distributed distinct aggregation algorithms for queries with multiple distinct functions **Mar.2022-July.2022**.
   - Optimize performances of aggregate functions for query that without group-by keys by loop unrolling and SIMD **April.2022-July.2022**.
   - Improve data locality for hash-aggregation by designing and implementing row stores for aggregated intermediate partial states **July.2022-Sept.2022**,
   - Optimize HashTable vectorization implementations of distributed HashJoin **Aug.2022-**.


- Software engineer intern at [Amazon AWS AI Lab(ShangHai)](https://www.amazonaws.cn/en/ailab/)                                  
   - Contribute to numpy-compatible operators for [MXNet](https://github.com/apache/incubator-mxnet)(July.2019~Aug.2019).

- Software engineer intern at [PerfxLab(Beijing)](https://perfxlab.com/)                                 
   - Implement column-row seperatable gaussian filter based on OpenCL (Mar.2019~May.2019).
   - Tune performance specifically for [AMD GCN arch GPU](https://www.amd.com/zh-hans/technologies/gcn)(Jun.2018-Aug.2018).

- Research Assistant at [Institute of Computing Technology](http://www.ict.cas.cn/)
   - Develop and optimize high-performance libraries on ARM CPUs which is compatible with [Intel IPP](https://www.intel.com/content/www/us/en/developer/tools/oneapi/ipp.html)(May.2017-Aug.2017). 

# Research Projects & Publications 
- [Implementation and Optimization of Multi-dimensional Real FFT on ARMv8 Platform]({{ site.url }}./ICA3PP18.pdf). 
  - **Sept.2017-Sept.2019**
  - **Author List**: **Wang Xiao** and Jia Haipeng and Li Zhihao and Zhang Yunquan. [ICA3PP18](http://www.wikicfp.com/cfp/servlet/event.showcfp?eventid=76333&copyownerid=117247).
  - **Brief introduction**: RealFFT is a high performance real number FFT library which supports 11 kinds of 1-3 dimensional float/double algorithms on both ARMv8 and x86 CPUs. It could outperforms [FFTW](https://www.fftw.org/) on ARMv8 CPUs at that time.

- [Efficient parallel optimizations of a high-performance SIFT on GPUs]({{ site.url }}./JPDC.pdf). 
  - **July.2017-Sept.2017**
  - **Author List**: Zhihao Li and Haipeng Jia and Yunquan Zhang and Shice Liu and Shigang Lia and **Xiao Wang** et al. [JPDC19](https://www.sciencedirect.com/journal/journal-of-parallel-and-distributed-computing)
  - **Brief introduction**; HartSift is a high-performance SIFT implementation that achieves higher performances than its counterpart in [OpenCV](https://opencv.org/), [SiftGPU](https://github.com/pitzer/SiftGPU), [CudaSift](https://github.com/Celebrandil/CudaSift). 

- [AutoFFT: A Template-Based FFT Codes Auto-Generation Framework for ARM and X86 CPUs]({{ site.url }}./SC19.pdf). 
  - **July.2018-July.2019**
  - **Authors List**: Zhihao Li, Haipeng Jia, Yunquan Zhang, Tun Chen, Liang Yuan, Luning Cao, **Xiao Wang**. [SC19](https://sc19.supercomputing.org/).
  - **Brief introduction**: AutoFFT is a template-based FFT auto-generation framework that acheive significant performance improvements on various CPUs and contributes to many Chinese vendor's library.

- [MVUC: An Interactive System for Mining and Visualizing Urban Co-locations]({{ site.url }}./WAIM16.pdf). 
  - **Oct.2014-July.2014**
  - **Authors List**: **Xiao Wang**, Hongmei Chen, Qing Xiao. [WAIM16](https://dblp.org/db/conf/waim/waim2016-1.html).
  - **Brief introduction**: MVUC proposes a data mining visualization method for spatial co-location patterns mined from urban datasets.

- [Virtual machine placement strategy using cluster-based genetic algorithm](https://www.sciencedirect.com/science/article/abs/pii/S0925231220312005). 
  - **Oct.2015-July2016**
  - **Athors List**: Binbin Zhang, **Xiao Wang**, Hao Wang. [Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing)
  - **Brief introduction**: This work proposes a cluster-based genetic algorithm to optimize migration strategies for virtual machines.

- [Perforamnce modeling and tunning of OpenBLAS on TianHe-3 superComputer FT2000 CPUs](https://github.com/xianyi/OpenBLAS)
  - **Oct.2018-Nov.2018**
  - **Brief introduction**: Develop and tune four GEMM(SCZD-GEMM) of L3-BLAS from OpenBLAS on FT2000+ CPUs achieving near peak theorical performances.

# Traveling
- I am enjoy travelling and observe what is happening in our planet. Currently I main travel within China, I hope to left my footprints on each continets in the future. Regions I have been include:
  - **China**: Beijing, Shanghai, Chongqing, Tianjin, Shenzhen, Zhuhai, Guangzhou, Huhhot, Kunming, Dali, HeFei, Zhengzhou, Shangqiu, Xinxiang, Kaifeng, Nanyang.
  - **The United States**: Denver, Colorado, Los Angeles, Chicago, 
  - **Italy**: Rome, Venice. 
  - **France**: Paris, 
  - **Germany**: Luxembourg, Heidelberg.
  - **Switzerland**: Interlaken, 

# Contact 
- Email Address: shawnWangCS@outlook.com 

# Resume 
Here is long version [Resume_Long_pdf_version]({{ site.url }}./wangxiao.pdf) with more details.
