# MAMA_NET_Pytorch
The official respository for our TMI Paper MAMA Net: Multi-scale Attention Memory Autoencoder Network for Anomaly Detection.

Code will be added here soon.

OC-SVM [7] is conducted with the code (https://github.com/mmasinas/ocSVM).  
VGG16/ResNet101 classification model is from the code (https://github.com/kuangliu/pytorch-cifar).  
Dense-UNet [28] is conducted with the code (https://github.com/UCSD-AI4H/COVID-CT).  
Inf-Net [34] is from the code (https://github.com/DengPingFan/Inf-Net).  
Zheng [33] is implemented with the code (https://github.com/sydney0zq/covid-19-detection).  
The AE-VGG16 and AE-ResNet101 are implemented by us based on the Pytorch library.  
TSC and StackRNN [2] are from the code (https://github.com/StevenLiuWen/sRNN_TSC_Anomaly_Detection).  
MemAE [15] is from the code (https://github.com/donggong1/memae-anomaly-detection) and (https://github.com/h19920918/memae).  
The code of [44] is available at (http://dei-s2.dei.uminho.pt/pessoas/csilva/brats_cnn/).  

For COVID-19 CT [28] experiments, the training set only includes the non-COVID cases that contains 463 images with a composition of 36 images from LUNA, 195 from MedPix, 202 from PMC, and 30 from Radiopaedia. And the test set includes non-COVID samples that has168 CT images (164 of them from LUNA dataset and the rest 4 from Radiopaedia) and 100 COVID CT images from SIRM COVID-19 Database.  

https://luna16.grand-challenge.org/  
https://medpix.nlm.nih.gov/home  
https://www.ncbi.nlm.nih.gov/pmc/  
https://radiopaedia.org/articles/covid-19-3  
https://www.sirm.org/category/senza-categoria/covid-19/  
