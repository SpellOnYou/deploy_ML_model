# ML-deployment

- repo for deploy ML model
- Not focusing on enhance accuracy but on `deploying model` 


<table>
  <tr>
    <td>Building ML Powered App: Going from Idea to Product</td>
     <td>TinyML: ML with TFLite on Android and Ultra-Low-Power Microcontrollers</td>
     <td>Practical DL for Cloud, Mobile, and Edge</td>
  </tr>
  <tr>
    <td><img src="https://github.com/SpellOnYou/SpellOnYou.github.io/blob/master/assets/images/ml-app.jpg" width=270 height=300></td>
    <td><img src="https://github.com/SpellOnYou/SpellOnYou.github.io/blob/master/assets/images/tinyml.jpg" width=270 height=300></td>
    <td><img src="https://github.com/SpellOnYou/SpellOnYou.github.io/blob/master/assets/images/cloudmobile.jpg" width=270 height=300></td>
  </tr>
 </table>


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
	- [Reddit : Deploying Pytorch models using Tensorflow Serving
](https://www.reddit.com/r/MachineLearning/comments/al0v4r/p_deploying_pytorch_models_using_tensorflow)
- [Medium: Converting a Simple Deep Learning Model from PyTorch to TensorFlow](https://towardsdatascience.com/converting-a-simple-deep-learning-model-from-pytorch-to-tensorflow-b6b353351f5d)
- [Stackoverflow: How do I change the Signatures of my SavedModel without retraining the model?](https://stackoverflow.com/questions/42801551/how-do-i-change-the-signatures-of-my-savedmodel-without-retraining-the-model)
- [Migrate your tensorflow from 1.x to 2.x](https://www.tensorflow.org/guide/migrate)
- [Serving tensorflow model](https://www.tensorflow.org/tfx/serving/serving_basic)
- [ResearchGate: How to connect AWS to an android app?](https://www.researchgate.net/post/How_to_connect_AWS_to_an_android_app)
- [AWS: Android Sagemaker developer resources](https://aws.amazon.com/sagemaker/developer-resources/)
