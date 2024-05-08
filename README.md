# Classical Piano Composer

This project allows you to train a neural network to generate midi music files that make use of a single instrument


## Training

To train the network you run **lstm.py**.

```
python lstm.py
```

**NOTE**: You can stop the process at any point in time and the weights from the latest completed epoch will be available for text generation purposes.

## Generating music

Once you have trained the network you can generate text using **predict.py**

```
python predict.py
```
