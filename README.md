## Summarizer

Text summarization in Keras

#### Basic NN in Keras

A first step to Keras example: https://machinelearningmastery.com/tutorial-first-neural-network-python-keras/

`basic_keras.py` is a copy of the code.

#### AWS Deep Learning AMI

A blog post on how to launch a Deep Learning AMI and connect it via Jupyter Notebook:
https://aws.amazon.com/blogs/ai/the-aws-deep-learning-ami-now-with-ubuntu/

Use following command to transfer the data to EC2.

```
scp -i <your .pem file name> ~/Downloads/pima-indians-diabetes.csv ubuntu@<Your instance DNS>:~
```

A screenshot from my instance.
[screenshot](screenshot.png)
