# NNlib
Flux re-exports all of the functions exported by the [NNlib](https://github.com/FluxML/NNlib.jl) package.

## Activation Functions
Non-linearities that go between layers of your model. Note that, unless otherwise stated, activation functions operate on scalars. To apply them to an array you can call `σ.(xs)`, `relu.(xs)` and so on.

```@docs
NNlib.elu
NNlib.gelu
NNlib.celu
NNlib.rrelu
NNlib.relu6
NNlib.leakyrelu
NNlib.logcosh
NNlib.logsigmoid
NNlib.sigmoid
NNlib.hardsigmoid
NNlib.hardtanh
NNlib.relu
NNlib.selu
NNlib.softplus
NNlib.softsign
NNlib.swish
NNlib.mish
NNlib.lisht
NNlib.trelu
NNlib.tanhshrink
NNlib.softshrink
```

## Softmax
```@docs
NNlib.softmax
NNlib.logsoftmax
```

## Pooling
```@docs
NNlib.maxpool
NNlib.meanpool
```

## Convolution
```@docs
NNlib.conv
NNlib.depthwiseconv
```
