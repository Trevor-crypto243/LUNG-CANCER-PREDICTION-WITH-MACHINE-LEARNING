<h1>IMAGE DENOISING USING MACHINE LEARNING</h1>
This codebase provides an implementation of image denoising using deep learning. Specifically, we use a convolutional neural network (CNN) to learn a mapping between noisy and denoised images .

<h2>Requirements</h2>
This codebase requires the following libraries:

<ul>
<li>Tensorflow</li>
<li>Keras</li>
<li>Numpy</li>
<li>OpenCV</li>
</ul>

<h2>Usage</h2>
To run the image super-resolution code, follow these steps:

<ol>
<li>Clone this repository to your local machine.</li>
<li>Install the required libraries using `pip install tensorflow keras numpy opencv-python`.</li>
<li>Open the `super_resolution.py` file in a Python IDE.</li>
<li>Modify the `input_image_path` variable to point to the low-resolution input image you want to upscale.</li>
<li>Modify the `output_image_path` variable to specify the output location for the high-resolution image.</li>
<li>Modify the `scale_factor` variable to set the scaling factor for the super-resolution algorithm.</li>
<li>Run the `super_resolve` function.</li>
<li>The high-resolution image will be saved to the specified output path.</li>
</ol>

<h2>Evaluation</h2>
We can evaluate the performance of the image super-resolution using the following metrics:

<ul>
<li>Peak Signal-to-Noise Ratio (PSNR)</li>
<li>Structural Similarity Index (SSIM)</li>
<li>Mean Squared Error (MSE)</li>
</ul>

To calculate these metrics, follow these steps:
<ol>
<li>Modify the evaluate function to set the input and output paths for the images, </li>
<li>Run the evaluate function.</li>
<li>The PSNR, SSIM, and MSE scores will be printed to the console.</li>
</ol>

