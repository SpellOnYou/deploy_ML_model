# ML-deployment

- repo for deploy ML model
- Not focusing on enhance accuracy but on `deploying model` developed via Pytorch and Tensorflow

## 1. Website deployment

### Test [here](https://my-city-classifier.onrender.com/)

branch [website](https://github.com/SpellOnYou/deploy_ML_model/tree/website/)

## 2. Converting Pytorch to Tensorflow 

1. convert pytorch params and models to onnx format (with pytorch model)
2. onnx file to `checkpoint meta` file of tensorflow
3. meta to tensorflow `protbuf`

You can find whole the code here: [Colab](https://colab.research.google.com/drive/1SxlrvdVj8ozRo27dnwfAju83q5qlwZZg)

branch [onnx](https://github.com/SpellOnYou/ML-toy-project/tree/onnx/)

---

#### Reference

- [Medium: Running pytorch models in production](https://medium.com/styria-data-science-tech-blog/running-pytorch-models-in-production-fa09bebca622)
  - [Origin reddit article](https://www.reddit.com/r/MachineLearning/comments/al0v4r/p_deploying_pytorch_models_using_tensorflow
- [Migrate your tensorflow from 1.x to 2.x](https://www.tensorflow.org/guide/migrate)
- [Serving tensorflow model](https://www.tensorflow.org/tfx/serving/serving_basic)
