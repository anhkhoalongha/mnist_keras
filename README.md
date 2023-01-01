# MNIST KERAS
## The basic model with deep learning is built with keras
![structure](https://github.com/anhkhoalongha/mnist_keras/blob/main/structure.png](https://github.com/anhkhoalongha/mnist_keras/blob/main/structure.png?raw=true)
## Parameter

aug= ImageDataGenerator(rotation_range=0.18, zoom_range=0.15, width_shift_range=0.2, horizontal_flip=True)

lr=1e-3

epoch=10

batch_size=64

opt= SGD(learning_rate=lr, momentum=0.9)

model.compile(optimizer=opt, loss='categorical_crossentropy', metrics='accuracy')

## Evaluate
accuracy: 0.9904000163078308
