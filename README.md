# Deepfakes dataset 

Author: TACKHYUN JUNG, SANGWON KIM

Status: Stop

We are offering an dataset for deepfake detection based on frames that contains 8 videos.

The target in the video was marked in the '/images'

# Benchmark in DeepVision(v1)

## Case1:
![fig 1](https://user-images.githubusercontent.com/41291493/71501929-7cb7d900-28b0-11ea-8dd5-a373bfbb2cd3.png)

We conducted an experiment on another Deep Fakes video with DeepVision on the same conditions as the previous experiment. As a result, the EAR value was changed as shown in figure. At about 9 seconds after the measurement began, a blink was detected once, and since then, the EAR level has remained constant. The number of blinks (/min) and the period (/sec) measured in experiment were discovered as significantly lower than the information (number, cycle, etc) of the actual human blink corresponding to the condition (female+40-50+Static+AM). Thus, it was determined as “Fake”.

### References

* DeepVision: Deepfakes Detection Using Human Eye Blinking Pattern
(https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9072088a)
