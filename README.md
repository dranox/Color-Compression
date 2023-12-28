# Color-Compression
Implement a program to reduce the number of colors in an image using the K-Means algorithm
Thus, the number of colors in an RGB image can be $256^3 \approx 1.7 \times 10^7$. With a fairly large number of colors, storing images may incur storage costs. Therefore, the problem is to reduce the number of colors to represent the image so that the image content is preserved as much as possible.

Give the image as follows:

![img](https://i.ibb.co/PZgqGDh/project01-new.png)

In the example above, the number of colors for the original image is 81705 colors. After reducing the number of colors to 7, the image is no longer detailed but still basically preserves the content of the original image.

To reduce the number of colors, we need to find substitutes for a group of colors. Specifically, in the case of RGB images, we need to group pixels $(\mathbb{R}^3)$ and choose a representative for each group. Thus, the above problem becomes a grouping of vectors.
