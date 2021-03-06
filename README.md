NNCam
=====

![gif](https://i.imgur.com/H3IMUHR.gif)

**NNCam** is a Unity sample project that implements a virtual background
feature (background removal for webcams) using the [Barracuda] inference
engine.

[Barracuda]: https://docs.unity3d.com/Packages/com.unity.barracuda@latest

NNCam uses the [BodyPix] human segmentation model for background removal. This
sample shows how to run similar models without CPU-side overhead.

[BodyPix]: https://blog.tensorflow.org/2019/11/updated-bodypix-2.html

System Requirements
-------------------

- Unity 2020.2
- Barracuda 1.2

How To Run
----------

The ONNX model file is not contained in this repository to avoid hitting the
storage quota. Run [this Colab notebook] to convert the original BodyPix models
to ONNX, then put the output file into `Assets/ONNX`.

[this Colab notebook]:
  https://colab.research.google.com/drive/1ikOMoqOX7TSBNId0lGaQ_kIyDF2GV3M3?usp=sharing 
