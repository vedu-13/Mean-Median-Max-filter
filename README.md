# Mean-Median-Max-filter

Mean Filter: Uses a kernel where each element is equal to 1 / (kernel_size * kernel_size). The image is convolved with this kernel using cv2.filter2D().

Median Filter: This filter replaces each pixel with the median of the surrounding pixels in a given window. It's implemented using the scipy.ndimage.median_filter() function.

Max Filter: Similar to the median filter, but instead of using the median, this filter takes the maximum value in the surrounding pixels. It's implemented using scipy.ndimage.maximum_filter().
