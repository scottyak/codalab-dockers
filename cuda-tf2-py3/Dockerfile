# Believed to be based on 
# https://github.com/tensorflow/tensorflow/blob/master/tensorflow/tools/dockerfiles/dockerfiles/gpu.Dockerfile
FROM tensorflow/tensorflow:2.2.0-gpu

RUN python3 -m pip install --upgrade pip
RUN python3 -m pip install \
    pyyaml==5.3.1 \    
    pandas==1.1.0 \
    scikit-learn==0.23.1 \
    xgboost==1.1.1 \
    Pillow==7.2.0 \
    matplotlib==3.3.0 \
    lightgbm==2.3.1 \
    powerlaw==1.4.6 \
    tensorflow-hub==0.9.0
