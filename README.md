This is the official code implementation of the paper <<Sub-diffraction-limited single-photon 3D imaging based on domain features extraction network at kilometer-scale distance>>.
The code and simulated data are open - sourced. The real data are not open - sourced due to the project reasons. 
### data simulation
The simulation method of the data set is borrowed from Nonlocal(https://github.com/JiayongO-O/PENonLocal)
### Test data
The test dataset can be downloaded by https://pan.baidu.com/s/1pqLfiiyR50vZK-MUjqZklg?pwd=buft 提取码: buft
###  Test the overall process program.
python demo.py
### training code
python train.py
tips:Overfitting is very likely to occur in actual training, and a smaller learning rate is recommended.
### parameter modification can be found in CFG in train.py
# Long-distance-single-photon-3D-imaging
