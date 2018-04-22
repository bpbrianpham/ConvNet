# MachineLearningLab4
I performed these tests with 6 epochs instead of 12 epochs due to the lack of GPU

1.  (25 points) a 3x3 convolution layer with 4 convolutions followed by a softmax
    Test Accuracy: 0.9859
    Test Loss: 0.0442811590289

2.  (25 points) a 3x3 convolution with 32 convolutions followed by a softmax
    Test accuracy: 0.9894
    Test loss: 0.0325783970155

3.  (25 points) a 3x3 convolution layer with 32 convolutions followed by a 2x2 max pool followedby softmax
    Test accuracy: 0.99
    Test loss: 0.0298664326341
    
    
The Test Results were as follows:

x_train shape: (60000, 28, 28, 1)
60000 train samples
10000 test samples
Train on 60000 samples, validate on 10000 samples
Epoch 1/6
60000/60000 [==============================] - 88s 1ms/step - loss: 0.3604 - acc: 0.8872 - val_loss: 0.0821 - val_acc: 0.9749
Epoch 2/6
60000/60000 [==============================] - 100s 2ms/step - loss: 0.1421 - acc: 0.9573 - val_loss: 0.0611 - val_acc: 0.9813
Epoch 3/6
60000/60000 [==============================] - 91s 2ms/step - loss: 0.1095 - acc: 0.9671 - val_loss: 0.0511 - val_acc: 0.9829
Epoch 4/6
60000/60000 [==============================] - 89s 1ms/step - loss: 0.0968 - acc: 0.9709 - val_loss: 0.0499 - val_acc: 0.9845
Epoch 5/6
60000/60000 [==============================] - 93s 2ms/step - loss: 0.0855 - acc: 0.9747 - val_loss: 0.0438 - val_acc: 0.9856
Epoch 6/6
60000/60000 [==============================] - 96s 2ms/step - loss: 0.0765 - acc: 0.9771 - val_loss: 0.0443 - val_acc: 0.9859
Test loss: 0.0442811590289
Test accuracy: 0.9859
Train on 60000 samples, validate on 10000 samples
Epoch 1/6
60000/60000 [==============================] - 211s 4ms/step - loss: 0.2724 - acc: 0.9174 - val_loss: 0.0673 - val_acc: 0.9801
Epoch 2/6
60000/60000 [==============================] - 211s 4ms/step - loss: 0.0939 - acc: 0.9722 - val_loss: 0.0441 - val_acc: 0.9853
Epoch 3/6
60000/60000 [==============================] - 198s 3ms/step - loss: 0.0676 - acc: 0.9799 - val_loss: 0.0392 - val_acc: 0.9865
Epoch 4/6
60000/60000 [==============================] - 203s 3ms/step - loss: 0.0539 - acc: 0.9832 - val_loss: 0.0354 - val_acc: 0.9882
Epoch 5/6
60000/60000 [==============================] - 200s 3ms/step - loss: 0.0482 - acc: 0.9856 - val_loss: 0.0337 - val_acc: 0.9895
Epoch 6/6
60000/60000 [==============================] - 196s 3ms/step - loss: 0.0392 - acc: 0.9881 - val_loss: 0.0326 - val_acc: 0.9894
Test loss: 0.0325783970155
Test accuracy: 0.9894
Train on 60000 samples, validate on 10000 samples
Epoch 1/6
60000/60000 [==============================] - 149s 2ms/step - loss: 0.2793 - acc: 0.9144 - val_loss: 0.0556 - val_acc: 0.9830
Epoch 2/6
60000/60000 [==============================] - 148s 2ms/step - loss: 0.0953 - acc: 0.9717 - val_loss: 0.0426 - val_acc: 0.9857
Epoch 3/6
60000/60000 [==============================] - 149s 2ms/step - loss: 0.0735 - acc: 0.9783 - val_loss: 0.0357 - val_acc: 0.9880
Epoch 4/6
60000/60000 [==============================] - 153s 3ms/step - loss: 0.0613 - acc: 0.9815 - val_loss: 0.0360 - val_acc: 0.9883
Epoch 5/6
60000/60000 [==============================] - 153s 3ms/step - loss: 0.0532 - acc: 0.9840 - val_loss: 0.0308 - val_acc: 0.9893
Epoch 6/6
60000/60000 [==============================] - 149s 2ms/step - loss: 0.0500 - acc: 0.9854 - val_loss: 0.0299 - val_acc: 0.9900
Test loss: 0.0298664326341
Test accuracy: 0.99
