# neural nets are weird - tried out on Windowns

Source code for the article [How to trick a neural network into thinking a panda is a vulture](https://codewords.recurse.com/issues/five/why-do-neural-networks-think-a-panda-is-a-vulture). 

**On Windows(tested with WIN7):** 
1. Install caffe
    a. Get caffe for windows by git clone https://github.com/Microsoft/caffe.git 
    b. Get miniconda 2.7 64-bit Windows installer and install miniconda2
        i.   conda install --yes numpy scipy matplotlib scikit-image pip
        ii.  pip install protobuf
        iii. conda install jupyter
2. Build caffe by following the instructions at https://github.com/Microsoft/caffe
3. Config your PythonPath ENV VAR to <caffe>\Build\x64\Release\pycaffe\
4. git clone https://github.com/brantz/neural-nets-are-weird
5. Open jupyter notebook
    a. $jupyter notebook --notebook-dir=<Unicode>
    b. Open neural-nets-are-weird-windows.ipynb
    c. You may need to modify the windows path in the notebook
6. Have fun!
