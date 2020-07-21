```
python3 --version
pip3 --version

python -m pip install --user virtualenv
virtualenv --version

# create a virtual env
virtualenv --system-site-packages -p python3 ./venv

# activate the virtual env
.\venv\Scripts\activate #  win
source ./venv/bin/activate  # sh, bash, ksh, or zsh

# upgrade pipls
pip install --upgrade pip

# install tensorflow
pip install --upgrade tensorflow

# check the installation
python -c "import tensorflow as tf;print(tf.reduce_sum(tf.random.normal([1000, 1000])))"
```
