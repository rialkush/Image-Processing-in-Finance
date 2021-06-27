# Image-Processing-in-Finance
This project is essentially the implementation of the paper [“Algorithmic Financial Trading with Deep Convolutional Neural Networks: Time Series to Image Conversion Approach”](https://www.researchgate.net/publication/324802031_Algorithmic_Financial_Trading_with_Deep_Convolutional_Neural_Networks_Time_Series_to_Image_Conversion_Approach/stats).  
In this project, we had created a novel algorithmic trading model CNN-TA using a 2-D Convolutional
Neural Network based on image processing properties. In order to convert financial time series into
2-D images, 12 different technical indicators each with different parameter selections are utilized.
Each indicator instance generates data for a 15 day period. As a result, 12x15 sized 2-D images are
constructed. Each image is then labelled as Buy, Sell or Hold depending on the hills and valleys of
the original time series.  
The results indicate that when compared with the Buy Hold Strategy and other common trading
systems over a long out-of-sample period, the trained model provides better results for stocks and
ETFs.  


