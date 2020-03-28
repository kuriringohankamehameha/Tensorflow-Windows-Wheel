# Tensorflow-Windows-Wheel
This is a Tensorflow 2.1.0 Wheel for Windows, CUDA 10.2 &amp; CC 5.0, Python 3.6, built for AVX2 type processors.

This works with my laptop, having a **Geforce GTX 940MX** GPU, and a newer version Intel Processor (hence the AVX2 flag in Bazel).
Ensure that your Python Version is **3.6.x**, Visual Studio version is of the *2019* edition, NVCC Version is 7, and Cuda Compatibility >= 5.0

## Google Drive URL
Download the `.whl` file from this link: https://drive.google.com/open?id=1sYDmc8vm7UjqLJfrFW3j4tnIcQIq6GqD

Simply place the wheel in your desired directory, and install it using `pip`:

```
pip install C:\PATH\TO\WHEEL\tensorflow-2.1.0-cp36-cp36m-win_amd64.whl
```

Enjoy!
