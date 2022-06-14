# 딥러닝 Workspace _ Zero-base DS School

> ## 사전 설정 : macbook m1 에서 tensorflow 설치

> ### 1. MacBook M1에 Xcode 설치
>> https://webnautes.tistory.com/1570

> ### 2. miniforge 설치 및 Visual Studio Code 연동
>> https://webnautes.tistory.com/1638

> ### 3. conda 가상환경 생성 및 활성화
>> [Developer.apple.com](https://developer.apple.com/metal/tensorflow-plugin/)
>> `conda create -n tensorflow-dev python=3.8`
>> `conda activate tensorflow-dev`

> ### 4. TensorFlow dependencies 설치
>> `conda install -c apple tensorflow-deps`

> ### 5. TensorFlow 설치
>> `python -m pip install tensorflow-macos`

> ### 6. Tensorflow-metal 플러그인 설치
>> `python -m pip install tensorflow-metal`

> ### 7. Tensorflow 버전 확인
>> `import tensorflow as tf`
>> `tf.__version__`

> ### 8. GPU 사용 가능여부 확인   
>> `tf.config.list_physical_devices('GPU')`
>> `[PhysicalDevice(name='/physical_device:GPU:0', device_type='GPU']` 라고 뜨면 사용 가능

## `Tensorflow` 및 `PyTorch` 강의 자료 백업
- 전체 자료 백업 완료


### 2022.05.30 강의자료 분류 및 재 업로드
- `Tensorflow` 강의 (10강)
- `PyTorch` 강의 (11강)



