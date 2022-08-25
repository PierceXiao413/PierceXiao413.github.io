---
# You don't need to edit this file, it's empty on purpose.
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default 
---

<!--
![xiaowang(王霄)]({{ site.url }}/wangxiao.jpg){:class="img-responsive"}
---!>
I am currently a full-time software engineer in [MaxCompute](https://www.alibabacloud.com/product/maxcompute), [Alibaba Cloud](https://my.alibabacloud.com/?utm_key=se_1007714444&utm_content=se_1007714444&gclid=EAIaIQobChMI4tKox43i-QIVEZhmAh02nwv1EAAYASAAEgIzbvD_BwE). I aim to build and optimze high-performance SQL execution engine. 

Before that, I achieve my master's degree from [State Key Laboratory of Computer Architecture](http://www.carch.ac.cn/), [Institute of Computing Technology, Chinese Academy of Sciences (SKL, ICT, CAS)](http://www.ict.cas.cn/) under the supervision of Prof.[Yunquan Zhang](https://scholar.google.com/citations?user=Cxg_yNoAAAAJ&hl=zh-CN). I obtain my B.E. in [Yunnan University](), worked with [Prof.Zhang binbin]()

I am interested in high-performance computing (performance tuning, SIMD optimization, GPGPU, GEMM, FFT) and building large-scale high-performance distributed computing systems.


# EDUCATIONS 
- 2017.9-Now, Institute of Computing Technology, Chinese Academy of Sciences, Master, High-Performance Computing, 

- 2013.9-2017.7, Yunnan University, B.Eng, Computer Science(3/121).

# Industry Experience
- Full-time Software engineer at [Alibaba Cloud](https://my.alibabacloud.com/?utm_key=se_1007714444&utm_content=se_1007714444&gclid=EAIaIQobChMI4tKox43i-QIVEZhmAh02nwv1EAAYASAAEgIzbvD_BwE) (July.2020-Now)
   - Design and implement adaptive distributed aggregation algorithm(hahs or sort) depending on data runtime statistical characteristics (1.1x~1.2x speedup in average for all job end to end time). 
   - Design and implement hash-based distributed distinct aggregation (2~50x speedup in average for all jobs end to end time)
   - Design and implement high performance vectorization implementation of 30 kinds of aggregate functions (around 2x speedup in average for all aggregation computations is achieved).
   - Optimize no-group by key aggregate function with Loop unrolling and SIMD (effective for numercial aggregate, 2~3 speedup for aggregation computations is achieved).
   - Design and implement row-stores for hashset randomly written operations.


# INTERNSHIPS 
- [Amazon AWS AI Lab(ShangHai)](https://www.amazonaws.cn/en/ailab/) (Jun.2019~Aug.2019)                                 
   - Contribute numpy-compatible operators to MXNet.

- [PerfxLab(Beijing)](https://perfxlab.com/) (Mar.2019~May.2019)                                
   - Implement column-row seperatable gaussian filter based on OpenCL.
   - Tune performance specifically for AMD GPU (GCN Architecture).

# PUBLICATIONS 

- [Implementation and Optimization of Multi-dimensional Real FFT on ARMv8 Platform](http://www.escience.cn/system/download/103329). 
- **Wang Xiao** and Jia Haipeng and Li Zhihao and Zhang Yunquan. [ICA3PP18](http://www.wikicfp.com/cfp/servlet/event.showcfp?eventid=76333&copyownerid=117247).
- RealFFT is a high performance Real number FFT library which supports 11 kinds of 1-3 dimensional float/double algorithms on both ARMv8 and x86 CPUs.

- [Efficient parallel optimizations of a high-performance SIFT on GPUs](http://www.escience.cn/system/download/102821). 
- Zhihao Li and Haipeng Jia and Yunquan Zhang and Shice Liu and Shigang Lia and **Xiao Wang** et al. [JPDC19](https://www.sciencedirect.com/journal/journal-of-parallel-and-distributed-computing)
- HartSift is a high-performance SIFT implementation that achieves higher performances than its counterpart in [OpenCV](https://opencv.org/), [SiftGPU](https://github.com/pitzer/SiftGPU), [CudaSift](https://github.com/Celebrandil/CudaSift). 

- [AutoFFT: A Template-Based FFT Codes Auto-Generation Framework for ARM and X86 CPUs](). 
- Zhihao Li, Haipeng Jia, Yunquan Zhang, Tun Chen, Liang Yuan, Luning Cao, **Xiao Wang**. [SC19](https://sc19.supercomputing.org/).
- AutoFFT is a template-based FFT auto-generation framework that acheive significant performance improvements on various CPUs and contributes to many Chinese vendor's library.

- [MVUC: An Interactive System for Mining and Visualizing Urban Co-locations](https://link.springer.com/content/pdf/bbm%3A978-3-319-39958-4%2F1.pdf). 
- **Xiao Wang**, Hongmei Chen, Qing Xiao. [WAIM16](https://dblp.org/db/conf/waim/waim2016-1.html).
- MVUC proposes a data mining visualization method for spatial co-location patterns on urban datasets.

- [Virtual machine placement strategy using cluster-based genetic algorithm](https://www.sciencedirect.com/science/article/abs/pii/S0925231220312005). 
-  Binbin Zhang, **Xiao Wang**, Hao Wang. [Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing)
-  This work propose a cluster-based genetic algorithm to optimize migration of virtual machines.

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

- Exploration on this world is exciting. In the past 25 years, I have left my footprints on three continents. One day, I believe that my footprints will be left on all continents. Currently, the cities include Beijing, Shanghai, Chongqing, Tianjin, Shenzhen, Zhuhai, Guangzhou, Huhhot, Kunming, Dali, HeFei, Denver, Colorado, Los Angeles, Chicago, Rome, Paris, Luxembourg, Interlaken, Venice, Heidelberg，Zhengzhou, Shangqiu, Xinxiang, Kaifeng, Nanyang.

<html>
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
    <h3>My Footprints Map :)</h3>
    <!--The div element for the map -->
    <div id="map"></div>
    <script>
// Initialize and add the map
function initMap() {
  // The location of Uluru
  var uluru0 = {lat: 39.900630, lng: 116.390563}; 
  // The map, centered at Uluru
  var map = new google.maps.Map(
      document.getElementById('map'), {zoom: 4, center: uluru0});
  // The marker, positioned at Uluru
  var marker0 = new google.maps.Marker({position: uluru0, map: map});
   
  //beijing
  var uluru1 = {lat: 22.542417, lng: 114.057303};
  var marker1 = new google.maps.Marker({position: uluru1, map: map});
  
  //shenzhen
  var uluru2 = {lat: 39.334260, lng: 117.340821}; 
  var marker2 = new google.maps.Marker({position: uluru2, map: map});
  
  //tianjin
  var uluru3 = {lat: 39.334260, lng: 117.340821}; 
  var marker3 = new google.maps.Marker({position: uluru3, map: map}); 
  
  //tai yuan
  var uluru4 = {lat: 37.872427, lng: 112.552177}; 
  var marker4 = new google.maps.Marker({position: uluru4, map: map});
  
  //chongqing
  var uluru5 = {lat: 29.444151, lng: 106.910327}; 
  var marker5 = new google.maps.Marker({position: uluru5, map: map});
 
  //zhuhai
  var uluru6 = {lat: 22.270883, lng: 113.580430}; 
  var marker6 = new google.maps.Marker({position: uluru6, map: map});
  
  //guangzhou
  var uluru7 = {lat: 23.136715, lng: 113.267635}; 
  var marker7 = new google.maps.Marker({position: uluru7, map: map});
  
  //huhot
  var uluru8 = {lat: 40.842896, lng:  111.743309}; 
  var marker8 = new google.maps.Marker({position: uluru8, map: map});
  
  //dali 
  var uluru9 = {lat: 25.610374, lng:  100.268560}; 
  var marker9 = new google.maps.Marker({position: uluru9, map: map});
  
  //heifei
  var uluru10 = {lat: 31.819264, lng:  117.231990}; 
  var marker10 = new google.maps.Marker({position: uluru10, map: map});
  
  //Denver
  var uluru11 = {lat: 39.744723, lng:  -105.000688}; 
  var marker11 = new google.maps.Marker({position: uluru11, map: map});
  
  //LA
  var uluru12 = {lat: 34.063402, lng:  -118.259329}; 
  var marker12 = new google.maps.Marker({position: uluru12, map: map});
  
  //Chi
  var uluru13 = {lat: 41.876097, lng:  -87.631034}; 
  var marker13 = new google.maps.Marker({position: uluru13, map: map});
  
  //Rome
  var uluru14 = {lat: 41.903853, lng:  12.490672}; 
  var marker14 = new google.maps.Marker({position: uluru14, map: map});
  
  //Pr
  var uluru15 = {lat: 48.858838, lng:  2.349462}; 
  var marker15 = new google.maps.Marker({position: uluru15, map: map});
  
  //Lux
  var uluru16 = {lat: 49.619619, lng: 6.134668}; 
  var marker16 = new google.maps.Marker({position: uluru16, map: map});
  
  //Interlake
  var uluru17 = {lat: 46.686913, lng:7.861864}; 
  var marker17 = new google.maps.Marker({position: uluru17, map: map});
  
  //Interlake
  var uluru22 = {lat: 46.686913, lng:7.861864}; 
  var marker22 = new google.maps.Marker({position: uluru22, map: map});
  
  //Had
  var uluru18 = {lat: 49.400569, lng:8.672626}; 
  var marker18 = new google.maps.Marker({position: uluru18, map: map});
  
  //Had
  var uluru19 = {lat: 49.400569, lng:8.672626}; 
  var marker19 = new google.maps.Marker({position: uluru19, map: map});
  
  //Fk 
  var uluru20 = {lat: 50.038050, lng:8.562087}; 
  var marker20 = new google.maps.Marker({position: uluru20, map: map});
  
  //Wis
  var uluru21 = {lat: 45.446384, lng:12.306891}; 
  var marker21 = new google.maps.Marker({position: uluru21, map: map});
  
  //Shanghai
  var uluru22 = {lat: 31.244270, lng:121.454611}; 
  var marker22 = new google.maps.Marker({position: uluru22, map: map});
  
  //Shangqiu
  var uluru23 = {lat: 34.412374, lng:115.650319}; 
  var marker23 = new google.maps.Marker({position: uluru23, map: map});
  
  //Nanyang
  var uluru24 = {lat: 32.991444, lng:112.514431}; 
  var marker24 = new google.maps.Marker({position: uluru24, map: map});
  
  //Zhengzhou
  var uluru25 = {lat: 34.747609, lng:113.609609}; 
  var marker25 = new google.maps.Marker({position: uluru25, map: map});
  
  //Xinxiang
  var uluru26 = {lat: 35.301482, lng:113.920327}; 
  var marker26 = new google.maps.Marker({position: uluru26, map: map});
  
  //Kaifeng
  var uluru27 = {lat: 34.796132, lng:114.304159}; 
  var marker27 = new google.maps.Marker({position: uluru27, map: map});
  
  //Kunming
  var uluru28 = {lat: 24.873976, lng:102.817274}; 
  var marker28 = new google.maps.Marker({position: uluru28, map: map});
}
    </script>
    <script async defer
    src="https://maps.googleapis.com/maps/api/js?key=AIzaSyAcROJn76-C6KwfmHEid1SdXYvJCECd13A&callback=initMap">
    </script>
  </body>
</html>


# CONTACT 

- Email Address: wangxiao17s@ict.ac.cn or lmzxiao@gmail.com

- Address: No.6 Zhong Guan Cun Ke Xue Yuan South Road, Haidian District, Beijing, China <br/>

# RESUME 
[Resume_pdf_version]({{ site.url }}./wangxiao.pdf)
