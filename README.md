# HSSR
**H**igh-**S**peed **S**piking **R**ecognition.


#### __$\bullet$ Introduction__

Frame cameras suffer from limited shutter speed and motion blur, which causes a substantial deficiency in latency and accuracy when recognizing high-speed objects. Spike
cameras have a high temporal resolution (i.e., 50𝜇𝑠), leading to a stronger capability of recording high-speed motions, as illustrated in the following,

<div align=center>
<img alt="Figure 1 width="50%" src="https://github.com/Evin-X/HSSR/blob/main/Figure/intro.png"/>
</div>
                                                                                              
<br/>
This work proposes a recognition framework that learns feature-level associations between short-term and long-term streams. The framework contains three components: a feature extractor, a spike encoder, and a decoder, as illustrated in the following,      
                                                                                                  
<div align=center> 
<img alt="Figure 2 width="50%" src="https://github.com/Evin-X/HSSR/blob/main/Figure/net.png"/>
</div>


#### __$\bullet$ Download Datasets__ 

This work constructs a large-scale spiking recognition dataset, which contains S-ImageNet and S-CARS.

S-ImageNet is collected using a high-speed motion platform set up in the laboratory. S-CARS is collected using a spike camera to capture high-speed moving vehicles in real-world scenarios.

Several samples in the S-ImageNet are visualized in the following,

<div align=center> 
<img alt="Figure 3 width="50%" src="https://github.com/Evin-X/HSSR/blob/main/Figure/samples.png"/>
</div>


----------------------------------
Datasets can be downloaded here,

1. [S-ImageNet](https://pkuorgcn-my.sharepoint.com/:u:/g/personal/jwz_pku_org_cn/EYjP_sf9i-RFodsPnVYKKPgB43fQR4ZIWP4gAhfXvqErDA?e=1OerGY) (>80G)
2. [S-CARS](https://pkuorgcn-my.sharepoint.com/:u:/g/personal/jwz_pku_org_cn/ET6H-AbLN65Pro47JkRod7YBSOSQLQGd3EpdqR9alaaDRQ?e=sl4ox8) (>5G)


#### __$\bullet$ Citation__

_Zhao J, Ye J, Zhang S*, Yu Z*, and Huang T. "Recognizing High-Speed Moving Objects with Spike Camera", in ACM International Conference on Multimedia. 2023._
