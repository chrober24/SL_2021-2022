# SL_2021-2022

This Repository contains a collection of Google Colab notebooks for various AI models which can be used for the Synthetic Landscapes Design Studio

## VQGAN + CLIP
This Notebook provides an implementation of VQGAN and OpenAI's CLIP for text to image translation. You can produce images by giving the model a written prompt. The AI will then attempt
to generate an image that it believes best matches the text.

## Neural_Style_Tf
This notebook provides a Tensorflow implementation of Neural Style Transfer. Provide the model with a form image and a style image and it will output a stylized result.

## ESRGAN
This notebook provides means of performing image superresolution based on pretrained models.

## Stylegan2_tutorial_train
This notebook provides a tensorflow implementation for training a Stylegan2 model. Models can be trained from scratch or by using transfer-learning with pretrained models.
It is recommended to use this in conjunction with Google Drive as the training process for Stylegan2 produces a large amount of data.

## Stylegan2_tutorial_generation
This notebook provides a tensorflow implementation for generating images from a Stylegan2 model. Functions are provided for single and multiple image generation as well as projection, 
truncation and interpolation. 
### NOTE: max resolution for the tf version of stylegan2 on Colab is 512x512

## Dataset_Prep
This notebook contains a collection of dataset preparation tools created by Derrick Shultz (linked in the notebook). There are various tools that help with scaling, cropping, formatting
and filtering images for various machine learning models (primarily stylegan and pix2pix). 
