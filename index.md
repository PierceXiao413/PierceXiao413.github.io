---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default 
---

![xiaowang(王霄)]({{ site.url }}/wangxiao.jpg){:class="img-responsive"}  
I am a second-year graduate student in [State Key Laboratory of Computer Architecture](http://www.carch.ac.cn/), [Institute of Computing Technology, Chinese Academy of Sciences (SKL, ICT, CAS)](http://www.ict.cas.cn/). I am supervised by Prof. [Yunquan Zhang](http://sourcedb.ict.cas.cn/cn/jssrck/201308/t20130822_3917018.html) on the high performance computing including performance tuning, SIMD optimization, GPGPU.

# EDUCATIONS 
- 2017.9-Now, Institute of Computing Technology, Chinese Academy of Sciences, Master., High Performance Computing, Supervisor: Prof. [Yunquan Zhang](http://sourcedb.ict.cas.cn/cn/jssrck/201308/t20130822_3917018.html).

- 2013.9-2017.7, Yunnan University, B.Eng, Computer Science(Top 5%). 

# RESEARCH PROJECTS 

- RealFFT Library, High performance implementation of 1D-3D float/double Real FFT on both ARMv8 and X86-64 CPU(Sept.2017~Oct.2018)

   - **Client**: HuaWei

   - **Role**: Core Developer 

   - Design and optimize 11 kind 1D~3D Float/Double Real FFT algorithms.

   - Implement Stockham Butterfly-Network for even-size real input data, including 11 real FFT kinds.

   - Optimize and Parallalize Real FFT computations with NEON and AVX on ARMv8/X86 CPUs.

   - Blocking computations with different level caches.

   - **Optimizing Effect**: Faster than [FFTW](http://www.fftw.org/) on ARMv8 platform around 34%~53% for 1D transforms, 10%~41% for 2D transforms, and achieve a nearly matchable performance than [MKL](https://software.intel.com/en-us/mkl/features/fft) for some kinds.

- A high-performance IPP library on ARMv8 architecture(May.2017~Aug.2017)

   - **Client**: HuaWei 

   - **Role**: Core Developer

   - Develop accuracy benchmark for performance primitives, such as e^x, ln(x), median filter, max operation, min operation, etc.

   - Parallelize and optimize these operations on ARMv8 CortexA57 CPU with Neon SIMD.

   - Optimize these operations with NEON intrinsics on ARMv8.

   - **Optimizing Effect**: Speedup achieved on ARMv8 is comparable with that achieved on X86 compared with the same performance benchmark.


- Transplant OpenBLAS GEMM on Tianhe-3 Supercomputer FT2000+ CPU(Oct.2018~Nov.2018) 

   - **Client**: National Supercomputing Center in Tianjin 

   - **Role**: Core Developer

   - Tune GEMM performance based on architecture of FT2000+ CPU.

   - Adjust P, Q, R parameter in block size of matrix multiplication. 

   - Manage vector registers in different ways, such as 4x4, 16x4 and 8x8. 

   - Tune instructions order.

   - **Optimizing Effect**: SGEMM, DGEMM, CGEMM, ZGEMM achieve 94.2%, 04.3%, 87.6%, 95.4% of theoretical peak performance.

# INTERNSHIPS 

- Amazon AWS AI Lab(ShangHai) (Jun.2019~Aug.2019)                                 

   - **Role**: Software Developer Intern

   - Contribute numpy-compatible operators to MXNet.

- PerfxLab(Startup in Beijing) (Mar.2019~May.2019)                                

   - **Role**: Core Developer.

   - A high-performance Gaussian Filter on AMD GPU based on OpenCL.

   - Implement column-row seperatable gaussian filter based on OpenCL.

   - Tune performance specifically for AMD GPU (GCN Architecture).

   - Faster than its counterpart of OpenCV around 21%-33%, especially when filter size is larger than 5.


# PUBLICATIONS 

- [Implementation and Optimization of Multi-dimensional Real FFT on ARMv8 Platform](http://www.escience.cn/system/download/103329). **Wang Xiao** and Jia Haipeng and Li Zhihao and Zhang Yunquan. International Conference on Algorithms and Architectures for Parallel Processing: 2018 ,338-353. Guangzhou, China. (ICA3PP18, CCF C; EI).

- [Efficient parallel optimizations of a high-performance SIFT on GPUs](http://www.escience.cn/system/download/102821). Zhihao Li and Haipeng Jia and Yunquan Zhang and Shice Liu and Shigang Lia and **Xiao Wang** et al. Journal of Parallel and Distributed Computing: 2019 ,124 ,78 - 91. (JPDC, CCF B; SCI, Impact Factor:1.815).

- [AutoFFT: A Template-Based FFT Codes Auto-Generation Framework for ARM and X86 CPUs](). Zhihao Li, Haipeng Jia*, Yunquan Zhang, Tun Chen, Liang Yuan, Luning Cao, **Xiao Wang**. The International Conference for High Performance Computing, Networking, Storage, and Analysis. November 17–22, 2019, Denver, CO, USA. (SC19, CCF A).

- [MVUC: An Interactive System for Mining and Visualizing Urban Co-locations](https://link.springer.com/content/pdf/bbm%3A978-3-319-39958-4%2F1.pdf). **Xiao Wang**, Hongmei Chen*, Qing Xiao. Conference on Web-Age Information Management 2016, 524-526. Nanchang, China. (WAIM16; Demo Paper, CCF C; EI).

# AWARDS 

- 2019 Merit Students Awards of University of Chinese Academy of Sciences.

- 2017 Outstanding Undergraduate Students Awards of Yunnan province(Top 5%).

- 2016 The CCF Outstanding Undergraduate Award.(Select 100 undergraduate students every year from all universities in China).

- 2015 First Prize in Contemporary Undergraduate Mathematical Contest in Modeling in Yunnan Province. 

- Merit Student of Yunnan University && First-class Scholarship.

# OTHER EXPERIENCE

- Serving as volunteer in Mental Health Therapy Center in Kunming.

- Serving as volunteer in water supply for foresters around University of Chinese academy of Sciences. 


# SKILLS

- Programming Language: proficient in c, SIMD(Neon/AVX), skilled at OpenCL/c++. 

- Development Tools: proficient in VIM, CMAKE, Git, gcc, g++, average at Google GTEST, Makefile. 

- English Level: Toefl 102, GRE 328.

# Traveling

- What always makes me feel excited is to travel around. The cities has my footprints includes: China:Beijing, Shanghai, Chongqing, Tianjin, Shenzhen, Zhuhai, Guangzhou, Huhhot, Kunming, Dali, HeFei; the United States Denver, Colorado, Los Angeles, Chicago; Eourpe: Rome, Paris, Luxembourg, Interlaken, Heidelberg.

  <head>
    <style>
      /* Set the size of the div element that contains the map */
      #map {
        height: 400px;  /* The height is 400 pixels */
        width: 100%;  /* The width is the width of the web page */
       }
    </style>
  </head>
  <body>
    <h3>My Google Maps Demo</h3>
    <!--The div element for the map -->
    <div id="map"></div>
    <script>
// Initialize and add the map
function initMap() {
  // The location of Uluru
  var uluru = {lat: -25.344, lng: 131.036};
  // The map, centered at Uluru
  var map = new google.maps.Map(
      document.getElementById('map'), {zoom: 4, center: uluru});
  // The marker, positioned at Uluru
  var marker = new google.maps.Marker({position: uluru, map: map});
}
    </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAcROJn76-C6KwfmHEid1SdXYvJCECd13A&callback=initMap">
    </script>
  </body>


# CONTACT 

- Email Address: wangxiao17s@ict.ac.cn or lmzxiao@gmail.com

- Address: No.6 Zhong Guan Cun Ke Xue Yuan South Road, Haidian District, Beijing, China <br/>

# RESUME 
[Resume_pdf_version]({{ site.url }}./wangxiao_cv_long.pdf)
