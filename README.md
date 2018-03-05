Keras Retinanet Docker
---------------------------
Simple docker files for training retinanet models on Keras.

Usage
=====
After running either the GPU or CPU images, you should be able to run something like the following from the container:

```
docker run --rm -it \
  -v `pwd`:`pwd`
  jcjimenez/keras-retinanet-docker \
  retinanet-train
```

