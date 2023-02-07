# Airbnb-price-category-prediction.

The problem here that we are going to predict the listing price based on the listing characteristics(images, summary) So we define three categories: beginner, plus, premium based on the created listing. Respectively we use 0, 1, 2 to denote these three categories.

The Inputs here are (two modalities): summary (text data), image (image data)

The Outputs here are (two predictions):type, price

Implementing deep learning using different neural networks (GRU, LSTM and Bi Directional layers for text data), (Conv2D, 
MaxPool2D for imagedata) that can predict the price or type or (price and type) of the house, using a multi‑modality model (text
and image) to cover a multi‑objectivemodel (predicting both price and type).
