# BVEC Model
Codes for paper _Comprehensive Maps of Material Stock Dynamics Reveal Increasingly Coordinated Urban Development in the Yangtze River Delta of China_

This paper presents a building volume estimation model based on convolutional neural networks (BVEC Model), leveraging multi-source geographic data such as nighttime light imagery and land use. First, we preprocess and spatially align the nighttime light imagery and building volume datasets to construct a comprehensive dataset. Second, based on the luminance index of the light data, the overall dataset is divided into different clusters, which are further divided into training and testing sets. Next, we train and test various models using the divided datasets. Finally, the trained model is employed to predict building volumes by inputting nighttime light imagery of the target region.

![markdown图](https://github.com/user-attachments/assets/8779f375-0cff-4f52-b1ee-978e652ce56f)

Nighttime lights dataset is available from 'https://doi.org/10.7910/DVN/YGIVCD'

Building heights and profile dataset is available from 'https://www.resdc.cn/data.aspx?DATAID=270'
