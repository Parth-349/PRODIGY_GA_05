
# Task-05: Neural Style Transfer

## Objective

Apply the artistic style of one image (e.g., a famous painting) to the content of another image using Neural Style Transfer. This deep learning method merges the content of a photo with the visual appearance of a painting to produce a stylized image.

## What is Neural Style Transfer?

Neural Style Transfer is a technique that uses a pre-trained Convolutional Neural Network (CNN), such as VGG19, to extract and recombine features from two images:

* A **content image** (e.g., a personal photo)
* A **style image** (e.g., a famous artwork)

The output is a new image that preserves the content while adopting the artistic style.

## Technologies Used

* Python
* TensorFlow
* Matplotlib
* Google Colab

## File Structure

Task-05

├── GA_05_Neural_Style_Transfer.ipynbr.ipynb — Colab-compatible notebook   
├── GA_05_Output.ipynb — Output  
├── stylized\_image.png — Output image    
└── README.md   

## How to Run the Project

1. Open the notebook (`GA_05_Neural_Style_Transfer.ipynb`) in **Google Colab**.
2. Run the cells step by step.
3. When prompted:

   * Upload one **content image**
   * Then upload one **style image**
4. The code will process the images, apply style transfer, and generate the final output.
5. The stylized image is displayed and saved as `stylized_image.png`.

## Features

* Two-step image upload for clarity
* Visual preview of both input images
* Uses pre-trained VGG19 from TensorFlow
* Outputs high-quality stylized image

Example Results
<table> <tr> <th>Content Image</th> <th>Style Image</th> <th>Stylized Output</th> </tr> <tr> <td><img src="https://github.com/Parth-349/PRODIGY_GA_05/blob/main/Content image.jpg?raw=true" width="250"/></td> <td><img src="https://github.com/Parth-349/PRODIGY_GA_05/blob/main/Style image.jpg?raw=true" width="250"/></td> <td><img src="https://github.com/Parth-349/PRODIGY_GA_05/blob/main/stylized_output image.png?raw=true" width="250"/></td> </tr> </table>

## References

* TensorFlow Neural Style Transfer Tutorial: [https://www.tensorflow.org/tutorials/generative/style\_transfer](https://www.tensorflow.org/tutorials/generative/style_transfer)
* VGG19 Paper (Simonyan & Zisserman, 2015): [https://arxiv.org/abs/1409.1556](https://arxiv.org/abs/1409.1556)

## Author

Parth Ubhad

GitHub: [Parth-349](https://github.com/Parth-349)

---


