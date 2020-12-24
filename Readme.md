Streamlit Image Classification
This repo comprises of trained DenseNet on cifar10 and then using Streamlit for Model serving.

Setting up the Environment




For Inference
we need Cifar-10 data for inference. Execute the below to generate 10 random images from cifar-10 test data.


Model Serving on Flask.

For Serving this model as a website. First generate test images by executing above commands and then.
python flask_api/app.py
