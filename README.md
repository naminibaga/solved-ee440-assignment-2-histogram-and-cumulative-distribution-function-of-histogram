Download Link: https://assignmentchef.com/product/solved-ee440-assignment-2-histogram-and-cumulative-distribution-function-of-histogram
<br>
<ol>

 <li>Histogram and cumulative distribution function of histogram.</li>

</ol>

For this problem, use the Lena image, <strong>2_1.bmp</strong>. Keep the range of the pixel values in [0,255]. The histogram of a digital image with gray levels in the range [0,L-1] is a discrete function h(k)=Nk, where Nk is the number of pixels in the image having gray level k. Write your own program to plot the histogram and the cumulative distribution function (cdf) of the pixel values of Lenna image. (Normalize the histogram to get the probability density function (pdf) and make sure it sums to one.)

<strong><em>Hint</em></strong>: This image contains three identical bands of size MxN. After loading the image, use one of the bands to plot the histogram. DO NOT use imhist or hist. You need to write your own code to plot the histogram.

<ol start="2">

 <li>Show (a) the three R, G, B images, and (b) the three H, S, V images of <strong>bmp</strong>.</li>

</ol>

<strong><em>Hint</em></strong>: To read in the image use: X=imread(‘2_2.bmp’,’bmp’). Notice that X will be a three dimensional array. You can then use <em>rgb2hsv</em> to convert the image to HSV.

<ol start="3">

 <li>Write your own Matlab program (do not use commercial image editing tools) to produce the negative of the <strong>bmp</strong> image. <strong>(35</strong> <strong>points)</strong></li>

</ol>

<strong><em>Hint</em></strong>: The negative of an image = (2^n – I)-1, where n is the number of bits and I is the intensity value of a pixel on this image.


