# Task 1: Edge Detection

## Choosing a filter

* A vast variety of filters are available on the internet some of which are 2X2 some 3X3 etc and all have their own advantages and disadvantages.

* I tried the laplacian filter but due to unsatisfactory results decided to not use it
![alt text](image-161.png)

* The most popular and obvious choices for a filter were **Sobel and Scharr**. Both of which are very efficient and give good results

## Padding

* I also decided to add one layer of zero padding to the image to keep the orginal dimensions intact

## Results till now

![alt text](image-158.png)
![alt text](image-159.png)
![alt text](image-160.png)

## Gaussian Blur

* i also tried using Gaussian blur before using the Sobel and Scharr but the results did not vary much and seemed to be an unnecessary computational cost

![alt text](image-162.png)

## Results

* The Sobel and Scharr gave the best results on their own with the Sobel being slighty better.