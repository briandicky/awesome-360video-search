# Awesome Architecture Search [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
<p align="center">
<img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

  A curated list of awesome 360-degree video papers and related resources. Inspired by [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), [awesome-deep-vision](https://github.com/kjw0612/awesome-deep-vision), [awesome-adversarial-machine-learning](https://github.com/yenchenlin/awesome-adversarial-machine-learning) and [awesome-deep-learning-papers](https://github.com/terryum/awesome-deep-learning-papers).

Over the past years, Virtual Reality (VR) products, such as Head-Mounted Displays (HMDs), become widely available. 
With the growing popularity of commercial VR products, more viewers are able to watch 360-degree videos with HMDs.
Majority of present global Internet traffic is due to video data ([Global Internet Phenomena](https://www.sandvine.com/trends/global-internet-phenomena/)). 
Streaming 360-degree videos further increases the Internet traffic amount, and becomes a hot research topic.
Hence, I collected some awesome papers and resources here!

----

## Table of Contents
- [Surveys](#surveys)
- [Systems](#systems)
- [Datasets](#datasets)
- [Open Software](#open-software)
- [Optimization](#optimization)
    - [Acquisition](#acquisition)
    - [Encoding](#encoding)
    - [Transmission](#transmission)
    - [Display](#display)
    - [Quality Assessments](#quality-assessments)
- [Applications](#applications)
- [Others](#others)

----

## Surveys
- R. Krevelen and R. Poelman, "A Survey of Augmented Reality Technologies, Applications and Limitations,"
*International Journal of Virtual Reality*, vol. 9, no. 2, pp. 1-20, June 2010.
[[pdf]](https://www.researchgate.net/publication/279867852_A_Survey_of_Augmented_Reality_Technologies_Applications_and_Limitations)

- A. Abbasi and U. Baroudi, "Immersive Environment: An Emerging Future of Telecommunications," 
*IEEE MultiMedia*, vol. 19, no. 1, pp. 80-80, January 2012.
[[pdf]](https://ieeexplore.ieee.org/document/6138575/)

- J. Apostolopoulos and P. Chou and B. Culbertson and T. Kalker and M. Trott and S. Wee, "The Road to Immersive Communication,"
*Proceedings of the IEEE*, vol. 100, no. 4, pp. 974-990, February 2012.
[[pdf]](https://ieeexplore.ieee.org/document/6153337/)

- C. Lee, A. Tabatabai, and K. Tashiro, "Free viewpoint video (FVV) survey and future research direction," 
*APSIPA Transactions on Signal and Information Processing*, vol. 5, no. 15, pp. 1–10, October 2015.
[[pdf]](https://www.cambridge.org/core/journals/apsipa-transactions-on-signal-and-information-processing/article/free-viewpoint-video-fvv-survey-and-future-research-direction/0E5F6708FD61193F78CF2BD3D6A58024)

- D. Chatzopoulos and C. Bermejo and Z. Huang and P. Hui, "Mobile Augmented Reality Survey: From Where We Are to Where We Go,"
*IEEE Access*, vol. 5, pp. 6917-6950, April 2017.
[[pdf]](https://ieeexplore.ieee.org/document/7912316/)

- M. Domański, O. Stankiewicz, K. Wegner and T. Grajek, "Immersive visual media — MPEG-I: 360 video, virtual navigation and beyond," 
in *Proc. of International Conference on Systems, Signals and Image Processing (IWSSIP'17)*, Poznan, Poland, May 2017, pp. 1-9.
[[pdf]](https://ieeexplore.ieee.org/document/7965623/)


## Systems
- B. Petry and J. Huber, "Towards effective interaction with omnidirectional videos using immersive virtual reality headsets,"
in *Proc. of the 6th Augmented Human International Conference (AH'15)*, Singapore, Singapore, March 2015, pp. 217-218.
[[pdf]](https://dl.acm.org/citation.cfm?id=2735785)

- P. Alface and M. Aerts and D. Tytgat and S. Lievens and C. Stevens and N. Verzijp and J. Macq, "16K Cinematic VR Streaming,"
in *Proc. of the 2017 ACM on Multimedia Conference (MM'17)*, Mountain View, CA, October 2017, pp. 1105-1112.
[[pdf]](https://dl.acm.org/citation.cfm?id=3123266.3123307)

- R. Anderson and D. Gallup and J. Barron and J. Kontkanen and N. Snavely and C. Hern{\'a}ndez and S. Agarwal and S. Seitz, "Jump: virtual reality video,"
*ACM Transactions on Graphics*, vol. 35, no. 6, pp. 198-211.
[[pdf]](https://dl.acm.org/citation.cfm?id=2980179.2980257)

- A. Ferworn, B. Waismark and M. Scanlan, "CAT 360 — Canine augmented technology 360-degree video system," 
in *Proc. of the 2015 IEEE International Symposium on Safety, Security, and Rescue Robotics (SSRR'15)*, West Lafayette, IN, October 2015, pp. 1-4.
[[pdf]](https://ieeexplore.ieee.org/document/7443003/)

- L. Gaemperle, K. Seyid, V. Popovic and Y. Leblebici, "An Immersive Telepresence System Using a Real-Time Omnidirectional Camera and a Virtual Reality Head-Mounted Display," 
in *Proc. of the 2014 IEEE International Symposium on Multimedia (ISM'14)*, Taichung, Taiwan, December 2014, pp. 175-178.
[[pdf]](https://ieeexplore.ieee.org/abstract/document/7033017/)

- E. Canessa and L. Tenze, "FishEyA: live broadcasting around 360 degrees,"
in *Proc. of the 20th ACM Symposium on Virtual Reality Software and Technology (VRST '14)*, Edinburgh, Scotland, November 2014, pp. 227-228.
[[pdf]](https://dl.acm.org/citation.cfm?id=2671135)

- K. Choi and K. Jun, "Real-time panorama video system using networked multiple cameras,"
*Journal of Systems Architecture: the EUROMICRO Journal*, vol. 64, no. C, pp. 110-121, March 2016.
[[pdf]](https://dl.acm.org/citation.cfm?id=2937627)

- N. Jiang, V. Swaminathan, and S. Wei, "Power Evaluation of 360 VR Video Streaming on Head Mounted Display Devices,"
in *Proc. of the 27th Workshop on Network and Operating Systems Support for Digital Audio and Video (NOSSDAV'17)*, Taipei, Taiwan, June 2017, pp. 55-60.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083173)

- D. Ochi, Y. Kunita, K. Fujii, A. Kojima, S. Iwaki, and J. Hirose, "HMD Viewing Spherical Video Streaming System,"
in *Proc. of the 22nd ACM international conference on Multimedia (MM '14)*, Orlando, FL, November 2014, pp. 763-764.
[[pdf]](https://dl.acm.org/citation.cfm?id=2654870)

- D. Ochi, Y. Kunita, A. Kameda, A. Kojima and S. Iwaki, "Live streaming system for omnidirectional video," 
in *Proc. of the 2015 IEEE Virtual Reality (VR'15)*, Arles, France, March 2015, pp. 349-350.
[[pdf]](https://ieeexplore.ieee.org/document/7223439/)

- F. Qian, L. Ji, B. Han, and V. Gopalakrishnan, "Optimizing 360 Video Delivery over Cellular Networks,"
in *Proc. of Workshop on All Things Cellular Operations, Applications and Challenges (ATC’16)*, New York City, NY, October 2016, pp. 1–6.
[[pdf]](https://dl.acm.org/citation.cfm?id=2980056)

- X. Xie and X. Zhang, "POI360: Panoramic Mobile Video Telephony over LTE Cellular Networks,"
in *Proc. of International Conference on Emerging Networking EXperiments and Technologies (CoNEXT’17)*, Incheon, Republic of Korea, December 2017, pp. 336–349.
[[pdf]](https://dl.acm.org/citation.cfm?id=3143381)

- X. Corbillon, G. Simon, A. Devlic and J. Chakareski, "Viewport-adaptive navigable 360-degree video delivery," 
in *Proc. of the 2017 IEEE International Conference on Communications (ICC'17)*, Paris, France, May 2017, pp. 1-7.
[[pdf]](https://ieeexplore.ieee.org/document/7996611/) [[software]](https://github.com/xmar/optimal-set-representation-viewport-adaptive-streaming)

- R. Schäfer, P. Kauff, R. Skupin, Y. Sánchez and C. weißig, "Interactive Steaming of Panoramas and VR Worlds,"
*SMPTE Motion Imaging Journal*, vol. 126, no. 1, pp. 35-42, February 2017.
[[pdf]](https://ieeexplore.ieee.org/document/7847668/)


## Datasets
- C. Wu and Z. Tan and Z. Wang and S. Yang, "A Dataset for Exploring User Behaviors in VR Spherical Video Streaming,"
in *Proc. of the 8th ACM on Multimedia Systems Conference (MMSys'17)*, Taipei, Taiwan, June 2017, pp. 193-198.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083210)

- X. Corbillon and F. Simone and G. Simon, "360Degreee Video Head Movement Dataset,"
in *Proc. of the 8th ACM on Multimedia Systems Conference (MMSys'17)*, Taipei, Taiwan, June 2017, pp. 199-204.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083215) [[software]](https://github.com/xmar/360Degree_Head_Movement_Dataset)

- Y. Rai and J. Guti{\'e}rrez and P. Callet, "A Dataset of Head and Eye Movements for 360 Degree Images,"
in *Proc. of the 8th ACM on Multimedia Systems Conference (MMSys'17)*, Taipei, Taiwan, June 2017, pp. 205-210.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083218)

- W. Lo and C. Fan and J. Lee and C. Huang and K. Chen and C. Hsu, "360-degree Video Viewing Dataset in Head-Mounted Virtual Reality,"
in *Proc. of the 8th ACM on Multimedia Systems Conference (MMSys'17)*, Taipei, Taiwan, June 2017, pp. 211-216.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083219) [[dataset]](https://nmsl.cs.nthu.edu.tw/360video/download.html)


## Open Software
### Codec
- M. Viitanen, A. Koivula, A. Lemmetti, A. Ylä-Outinen, J. Vanne, and T. Hämäläinen, "Kvazaar: Open-Source HEVC/H.265 Ensoftwarer,"
in *Proc.of the 2016 ACM on Multimedia Conference (MM'16)*, Amsterdam, The Netherlands, October 2016, pp. 1179-1182.
[[pdf]](https://dl.acm.org/citation.cfm?id=2973796) [[software]](https://github.com/ultravideo/kvazaar)

- High Efficiency Video Coding (HEVC) Test Model.
[[web]](https://hevc.hhi.fraunhofer.de/) [[software]](https://hevc.hhi.fraunhofer.de/svn/svn_HEVCSoftware/)

- HEVC Scalability Extension (SHVC) Test Model. 
[[web]](https://hevc.hhi.fraunhofer.de/shvc) [[software]](https://hevc.hhi.fraunhofer.de/svn/svn_SHVCSoftware/)

### Projection
- 360Lib
[[web]](https://mpeg.chiariglione.org/standards/mpeg-i/versatile-video-coding) 

- Facebook/Surround360
[[software]](https://github.com/facebook/Surround360)

- Samsung/360tools
[[software]](https://github.com/Samsung/360tools)

- X. Corbillon, F. Simone, and G. Simon, "360-Degree Video Head Movement Dataset,"
in *Proc. of the 8th ACM on Multimedia Systems Conference (MMSys'17)*, Taipei, Taiwan, June 2017, pp. 199-204.
[[pdf]](https://dl.acm.org/citation.cfm?id=3083215) [[software]](https://github.com/xmar/360Transformations)

### Packager

### Player

### Tracker

### Others


## Optimization

### Acquisition

### Encoding

### Transmission

### Display

### Quality Assessments

## Applications


## Others


----

## Contributing
<p align="center">
<img src="http://cdn1.sportngin.com/attachments/news_article/7269/5172/needyou_small.jpg" alt="We Need You!">
</p>

Please help contribute this list by contacting [me](https://briandicky.github.io/) or add [pull request](https://github.com/briandicky/awesome-360video-search/pulls)

Markdown format:
```markdown
(Conference paper)
- Author 1, Author 2 and Author 3, "Paper Name," 
in *Proc. of Conference Name (Series'Year)*, City, Nation, Month Year, pp. xxx-xxx.
[[pdf]](link) [[software]](link)
```

```markdown
(Journal paper)
- Auther 1, Auther 2 and Author 3, "Paper Name," 
*Journal Name*, vol. xxx, no. xxx, pp. xxx-xxx, Month Year. 
[[pdf]](link) [[software]](link)
```

```markdown
(webpage)
- Name
[[web]](link) [[software]](link)
```

----

## License
[![PDM](https://licensebuttons.net/p/mark/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Wen-Chih Lo](https://briandicky.github.io/) has waived all copyright and related or neighboring rights to this work.
