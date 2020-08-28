##### Estimation of Vehicle Roll Angle and Road Bank Angle Using Deep Neural Network

 In the vehicle driving situation, a road bank angle affects not only the vehicle roll dynamics but also the vehicle stability. For more stable and safe driving, accurate
and reliable estimation of vehicle states is critical. Conventional road bank-angle estimation methods typically employ a dynamic filter compensation which is quite accurate in estimating the steady-state driving conditions. However, in unstable driving conditions such as high-speed driving, it is not reliable much.
 The purpose of this research is proposing a novel method estimating vehicle roll angle and road bank angle using a deep neural network(DNN). In order to estimate the vehicle roll angle and road bank angle, among widely used vehicle onboard sensors, input data from five sensors are selected. The proposed deep neural network is trained using the input data acquired in various driving situations.
 In this research, data acquisition process and verification of estimation algorithm are conducted by simulation using a commercial vehicle model. The vehicle driving simulation and vehicle sensor data acquisition are accomplished by IPG Carmaker, which is one of the most well-known vehicle simulation tools. Modeling and training of the DNN model are results are accomplished by Keras in Python. 
 Results show that the performance of the proposed method using the DNN is more accurate in both vehicle roll angle and road bank angle estimations than conventional methods. Especially, the proposed method reveals a notable performance enhancement in the road bank angle estimation.
 
 ![images1](https://github.com/THLEE-KR/my_master_thesis/blob/master/thesis1.JPG)
 
 ![images2](https://github.com/THLEE-KR/my_master_thesis/blob/master/thesis2.JPG)
