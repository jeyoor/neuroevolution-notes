1. Install python3, python3-dev, python-dev, python-virtualenv, python-pip

2. Create virtual enviornment 

virtualenv -p python3 --system-site-packages ~/praj/py3env_tensorflow

3. Activate virtual env

source ~/praj/py3env_tensorflow/bin/activate

4. Install python3 tensorflow

pip install --upgrade https://storage.googleapis.com/tensorflow/linux/cpu/tensorflow-0.6.0-cp34-none-linux_x86_64.whl

NOTE: currently GPU support requires NVidia CUDA and CUDANN libraries. CUDANN seems to require separate registration on their website... closed source licenses?
