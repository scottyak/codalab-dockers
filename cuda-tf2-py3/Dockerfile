# Believed to be based on 
# https://github.com/tensorflow/tensorflow/blob/master/tensorflow/tools/dockerfiles/dockerfiles/gpu.Dockerfile
FROM tensorflow/tensorflow:2.2.0-gpu

RUN python3 -m pip install --upgrade pip
# ripser requires Cython to be installed first
RUN python3 -m pip install Cython==0.29.21   
RUN python3 -m pip install \
    pyyaml==5.3.1 \    
    pandas==1.1.0 \
    scikit-learn==0.23.1 \
    xgboost==1.1.1 \
    Pillow==7.2.0 \
    matplotlib==3.3.0 \
    lightgbm==2.3.1 \
    powerlaw==1.4.6 \
    tensorflow-hub==0.9.0 \
    tensorflow-addons==0.11.2 \
    ripser==0.5.4 \
    tensorflow-datasets==3.2.1 \
    tensorflow-probability==0.11.0 \
    torch==1.6.0 \
    torchvision==0.7.0
