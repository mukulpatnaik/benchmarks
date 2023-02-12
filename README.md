# benchmarks

Model Training Summary

Three different models were trained on MNIST and CIFAR-10 datasets using PyTorch on a device with mps. The results of the training are summarized below:

LeNet on MNIST

- Epoch: 1
- Batch size: 4,21
- Loss: 0.0733
- Train accuracy: 97.33%
- Validation accuracy: 97.77%
- Test accuracy: 97.39%
- Time / epoch without evaluation: 6.19 sec
- Total Training Time: 9.38 sec

MLP on MNIST

- Epoch: 1
- Batch size: 4,21
- Loss: 0.3499
- Train accuracy: 91.63%
- Validation accuracy: 93.48%
- Test accuracy: 92.15%
- Time / epoch without evaluation: 3.25 sec
- Total Training Time: 6.24 sec

VGG16 on CIFAR-10

- Epoch: 1
- Batch size: 1,406
- Loss: 2.0943
- Train accuracy: 31.80%
- Validation accuracy: 32.26%
- Test accuracy: 32.40%
- Time / epoch without evaluation: 1,405.05 sec
- Total Training Time: 2,340.54 sec
