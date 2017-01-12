# How to install Tensor stuff plus Spyder
Try to install Tensorflow,Tensorlayer,Spyder.

#Source by Chuanhao_Li

##1. 安装anaconda.
[官网链接。](https://www.continuum.io/downloads)

##2. 教训！一定要用Python 3.5版本啊！用Python 2.7 会出现 “段错误 已转储”
##3. 安装TensorFlow

具体详见[链接1](https://www.tensorflow.org/versions/r0.12/get_started/os_setup.html#using-conda),[链接2]( http://tensorlayer.readthedocs.io/en/latest/user/installation.html)。

###3.1 Create a conda environment called tensorflow:

if choose no at the last step， you need to add path use this command.

    export PATH=~/anaconda3/bin:$PATH
    
这里注意一定不要安装python2.7，我试过python2.7下安装TensorFlow和TensorLayer，出现错误
    
    # Python 3.5
    $ conda create -n tensorflow python=3.5
    
###3.2 Use Conda to install Tensorflow

    $ source activate tensorflow
    (tensorflow)$  # Your prompt should change

    # Linux/Mac OS X, Python 2.7/3.4/3.5, CPU only:
    (tensorflow)$ conda install -c conda-forge tensorflow
##4.Install TensorLayer

The simplest way to install TensorLayer is as follow, it will also install the numpy and matplotlib automatically.

    [stable version] pip install tensorlayer
    [master version] pip install git+https://github.com/zsdonghao/tensorlayer.git
##5.Install Spyder

    conda install spyder
    
