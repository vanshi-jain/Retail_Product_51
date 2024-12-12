# Retail Product Detection with FiftyOne x YOLOv8

Link to the Presentation [Slides](https://1drv.ms/p/s!ArS9zH4Hq5kfeNfrVGwLn3mgZcs?e=EEdI1A) for Dec 12 Meetup.

In today's fast-paced retail environment, automation at the checkout counter is becoming increasingly essential. Detecting and classifying products accurately can significantly enhance operational efficiency, reduce human error, and improve customer experience. This notebook demonstrates a streamlined approach to retail product detection using the Retail Product Checkout (RPC) dataset, which consists of 200 retail Stock Keeping Units (SKUs) spanning 17 meta categories, including puffed food, dried food, drinks, and more.

To achieve precise detection and classification, we leverage the powerful YOLOv8 model, renowned for its speed and accuracy in real-time object detection tasks. Additionally, the integration of FiftyOne, an open-source toolset for computer vision, allows us to simplify the data loading, training, evaluation, and visualization processes.

This notebook will guide you through the steps of:

- Loading and preparing the RPC dataset with FiftyOne.
- Training a YOLOv8 model for retail product detection.
- Evaluating model performance using FiftyOne.
- Visualizing detection results with easy-to-understand metrics and visual tools.
