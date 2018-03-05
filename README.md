Keras Retinanet Docker
---------------------------
Simple docker files for training retinanet models on Keras.

Usage
=====
Invoking the `retina-train` script from the docker container can be done like so:

```
docker run --rm -it \
  -v `pwd`:`pwd`
  jcjimenez/keras-retinanet-docker \
  retinanet-train
```

