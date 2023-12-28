# Requirements

 * Check the **requirements.txt** file.
 * For ONNX, if you have a NVIDIA GPU, then install the **onnxruntime-gpu**, otherwise use the **onnxruntime** library.
 * To use this model, you must have a model in the form of onnx. This GitHub does not include a model, so please contact us by email if you want to run it

# Installation
```shell
git clone https://github.com/jihyun-log/AI_Model-BebeFace_KOSA-project.git
cd AI_Model-BebeFace_KOSA-project
pip install -r requirements.txt
```
### ONNX Runtime
For Nvidia GPU computers:
`pip install onnxruntime-gpu`

Otherwise:
`pip install onnxruntime`


# 24 Hours Monitoring System -  Baby Status Detection

 * **24 Hours Monitoring System : Main**:
 ```shell
 python main.py
 ```

 * **Webcam Baby Status Detection**:
 ```shell
 python webcam_object_detection.py
 ```

 * **24 Hours Monitoring System : Alarm - Back, Negative Status Detection**:
 ```shell
 python webcam_alarm.py
 ```

 * **24 Hours Monitoring System : Capture and Alarm - Positive Status Detection**:
 ```shell
 python webcm_capture.py
 ```