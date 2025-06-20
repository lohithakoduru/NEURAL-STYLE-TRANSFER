# NEURAL-STYLE-TRANSFER

*COMPANY* : CODTECH IT SOLUTIONS 

*NAME* : KODURU LOHITHA

*INTERN ID* : CITS0D62 

*DOMAIN* : Artificial Intelligence

*DURATION* : 8 WEEKS

*MENTOR* : NEELA SANTOSH

** DESCRIPTION OF TASK 3:

In Task 3 of the internship, I implemented a Neural Style Transfer (NST) model to apply the artistic style of one image (like a painting) to another image (such as a photo of nature). This task was performed entirely in Jupyter Notebook using Python and leveraged TensorFlow 2, TensorFlow Hub, and Matplotlib for execution and visualization.

The core concept behind Neural Style Transfer is combining two types of image features: the content features from a real image and the style features from an artwork. The result is a new image that retains the subject of the original photo but adopts the texture, colors, and brushstroke patterns of the artistic style.

To perform this, I used a pre-trained model from TensorFlow Hub:
https://tfhub.dev/google/magenta/arbitrary-image-stylization-v1-256/2
This model takes two input tensors—content and style—and outputs a stylized image. I wrote helper functions to load .jpg or .jpeg images using the PIL library and convert them into tensors required for model processing. I resized the images to 512x512 pixels, normalized the pixel values, and ensured both inputs had the correct shape before passing them to the model.

After the model generated the stylized image, I used Matplotlib to display all three images: the original content image, the style image, and the resulting stylized output. The visual quality was impressive, showing how effectively deep learning models can be used for creative image transformation.

Neural Style Transfer has real-world applications in photo editing, creative arts, digital media, and augmented reality. Applications like Prisma, DeepArt, and other AI-based photo editors use similar models to let users convert selfies and landscape images into artwork styled like Picasso, Van Gogh, or any chosen aesthetic. It's also used in game development, animation, and fashion tech to explore creative possibilities.

The tools used in this task were:

Python

Jupyter Notebook

TensorFlow 2

TensorFlow Hub

PIL (Pillow) for image loading and resizing

Matplotlib for visualization

This task gave me practical exposure to computer vision tasks and deep learning model usage without needing to build or train models from scratch. It demonstrated the power of transfer learning and pre-trained models, which are crucial for efficient AI development.

Completing this task deepened my understanding of how neural networks process visual data and how style and content are treated differently in convolutional neural networks (CNNs). It also highlighted how creativity and AI intersect, making technology a powerful tool in the world of digital design.
