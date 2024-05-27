A place where a beginner learn computer vision.  
target:implementing an open source software for identifying moving objects  
First, we need to detect moving objects.  
There are three main steps:   
1.Background modeling: Identify static backgrounds in the video. This is done by analyzing a series of frames, aiming to find out which parts are static.  
2.Foreground detection: The algorithm will identify parts that do not match the background model, which are usually moving objects.  

3.Data processing: Noise is removed through filtering and thresholding, so that the information of moving objects can be accurately extracted.  

Then， implement target tracking.  

I select difference method to detect moving object.  
This is a simple and effective moving object detection technology，The core idea of which is to identify moving objects   
by comparing the differences between consecutive video frames.  
This is what I will accomplish first in the next month.  
