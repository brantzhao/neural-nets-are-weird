# neural nets are weird - tried out on Windows

This repository is forked from [jvns/neural-nets-are-weird](https://github.com/jvns/neural-nets-are-weird).
It is source code for the article [How to trick a neural network into thinking a panda is a vulture](https://codewords.recurse.com/issues/five/why-do-neural-networks-think-a-panda-is-a-vulture).

##On Windows(tested with WIN7):
1. Install caffe
 1. Get caffe for windows by git clone https://github.com/Microsoft/caffe.git 
 2. Get miniconda 2.7 64-bit Windows installer and install miniconda2
     1. conda install --yes numpy scipy matplotlib scikit-image pip
     2. pip install protobuf
     3. conda install jupyter
2. Build caffe by following the instructions at https://github.com/Microsoft/caffe
3. Config your PythonPath ENV VAR to <caffe>\Build\x64\Release\pycaffe\
4. git clone https://github.com/brantz/neural-nets-are-weird
5. Open jupyter notebook
 1. $jupyter notebook --notebook-dir=<Unicode>
 2. Open neural-nets-are-weird-windows.ipynb
 3. You may need to modify the windows path in the notebook
6. Have fun!
