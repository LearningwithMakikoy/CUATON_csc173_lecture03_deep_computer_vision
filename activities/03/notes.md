\# Lecture 03 Activity: Notes

Name: Marcus Miguel L. Cuaton · Student ID: 2023-1035



\## My photos (Parts 0 to 6) 4 photos

How many photos, and what each shows (one line each):

1. sign with a quote - took a picture at a slight angle

2\. painting - took a picture of a painting of a mom and a child

3\. coffee - a coffee drink 

4\. a4 paper - a colored a4 paper



\## My dataset (Part 7)

Categories: Soy Sauce vs. Vinegar

Photos per category: 21 soy sauce pictures and 21 vinegar pictures

How I took them (places, backgrounds, lighting, angles): I took photos of soy sauce and vinegar bottles in a cafe using a wooden table and some lighting conditions. I varied the camera angles and the distance between the camera and the bottles.



Final validation accuracy: transfer 1.00(100%) · from scratch 0.40 (40%)

The transfer learning performed significantly better despite having fewer trainable parameters since MobileNetV2 has already learned useful visual features from a large dataset. However, the from-scratch CNN had to learn these features using only a small collection of photos that I've gathered.





\## My kernel (Part 2c)

The numbers, and what it detects:

\[\[ 2,  1,  0],

&#x20;\[ 1,  0, -1],

&#x20;\[ 0, -1, -2]]

This kernel detects diagonal edges, particularly brightness transitions from the upper-left to the lower-right. Positive values respond to brighter regions in the upper-left, while negative values respond to brighter regions in the lower-right. It has a sum of zero, so it produces weak responses in areas with uniform brightness.



\## AI and outside help

List any AI tools, websites or classmates you used, and for what.

* ChatGPT (OpenAI): Used to explain CNN and Transformer concepts, clarify assignment instructions, assist with Python/TensorFlow code, troubleshoot errors, and help interpret model outputs.



* TensorFlow/Keras documentation: Used as a reference for understanding model layers, image preprocessing, and transfer learning.



* Google Colab/Jupyter Notebook: Used to execute the code, visualize results, and test the models.

