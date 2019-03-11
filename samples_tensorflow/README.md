# samples_tensorflow

TensorFlowを使っていろいろやってみたものたち。

## How to use

```sh
$ docker build -t samples_deeplearning_python docker/.
```

```sh
$ docker run -it --rm -v $(pwd):/tf/notebooks -p 8888:8888 samples_tensorflow
```
