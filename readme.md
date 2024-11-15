# ecg_i2s

Transform ECG Images to Signals

We organize the content into pypi packages，and you can directly install it from PyPI by executing the command  **pip install i2s-ecg** .
You also can learn more from our pypi address  **https://pypi.org/project/i2s-ecg/** .  

You can use this code to transform ECG images into 1D signals. Follow the instructions below to get started.

We recommend you to use the newest version of the code.

## Setup Instructions

### 1.**Create a Conda Environment**

We recommend using Python version 3.9.19.

   ```
conda create -n ecg python=3.9.19
   ```

Then you should activate the environment using:

   ```
conda activate ecg
   ```

### 2.**Install Required Packages**

Install the necessary packages using the following:

   - `scikit-learn==1.2.2`
   - `scikit-image`
   - `unzip`
   - `joblib`
   - `pandas`
   - `matplotlib`
   - `natsort`
   - `streamlit_cropper`
   - `scipy`
   - `numpy==1.25.2`
   - `pillow`
   - `natsort`

   Alternatively, you can use the `requirements.txt` file to install the required packages by running:

   ```bash
pip install -r requirements.txt
   ```

### 3.**Run the Code**

1. you can run the code by:

```
python -m i2s_ecg.run
```

2. you can also write your own program, for example:

```main.py
from i2s_ecg import run_app
run_app()
```

### 4.**use the streamlit app**
![for i2s_ecg](https://gitee.com/xzxg001/i2s_ecg/raw/master/for%20i2s_ecg.jpg)
We prepare a picture to show the usage of the app.

![i2s_ecg](https://gitee.com/xzxg001/i2s_ecg/raw/master/i2s_ecg.gif)
You can use the streamlit app to upload your ECG images and get the corresponding 1D signals.
