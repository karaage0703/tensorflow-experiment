
# Conclusion
...

# Results
...

## Preparation
Setup tensorflow-pi:
```sh
$ cd
$ git clone https://github.com/karaage0703/tensorflow-pi
$ cd tensorflow-pi/data
$ ./getCaltech101.sh 
$ python make_train_data.py 101_ObjectCategories
```

Clone this repository:
```sh
$ cd
$ git clone https://github.com/karaage0703/tensorflow-experiment
```

## MNIST CNN
Using `cnn_mnist.py` for cnn network
```sh
$ cp ~/tensorflow-experiment/20170815_experiment/cnn.mnist ~/tensorflow-pi/cnn.py
```

Train:
```sh
$ cd ~/tensorflow-pi/
$ python train.py
```


```
step 0, training accuracy 0.0508475, loss nan
step 1, training accuracy 0.0508475, loss nan
```


## Like CIFAR10 NN
...


## Like CIFAR10 NN
...