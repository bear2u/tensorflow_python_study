# tensorflow 실행 방법
## 설치 링크
[공식 링크](https://www.tensorflow.org/install/pip?lang=python3)
## virtual environment
```
virtualenv --system-site-packages -p python3 ./tensorflow
source ./tensorflow/bin/activate
```
## 설치 진행
```
pip install --upgrade tensorflow
pip install --upgrade pip
pip list
```
## 테스트
```
python -c "import tensorflow as tf; tf.enable_eager_execution(); print(tf.reduce_sum(tf.random_normal([1000, 1000])))"
```

## 나가기
```
deactivate
```
