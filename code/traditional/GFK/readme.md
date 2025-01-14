# Geodesic Flow Kernwl (GFK)

This is the implementation of Geodesic Flow Kernel (GFK) in both Matlab and Python.

## Matlab version

Just use `GFK.m`. Note that `getGFKDim.m` is the implementation of *subspace disagreement measurement* proposed in GFK paper.

## Python version

See the `GFK.py` file.

Requirements:
- Python 3
- Numpy and Scipy
- Sklearn
- **Bob**

**Note:** This Python version is wrapped from Bob: https://www.idiap.ch/software/bob/docs/bob/bob.learn.linear/stable/_modules/bob/learn/linear/GFK.html#GFKMachine.

Therefore, if you want to run and use this program, you should install `bob` by following its official instructions in [here](https://www.idiap.ch/software/bob/docs/bob/docs/stable/bob/bob/doc/install.html).

There are many libraries in bob. A minimum request is to install `bob.math` and `bob.learn` by following the instructions.

## Run

The test dataset can be downloaded [HERE](https://github.com/jindongwang/transferlearning/tree/master/code/traditional/data). Then, you can run the file.

### Reference

Gong B, Shi Y, Sha F, et al. Geodesic flow kernel for unsupervised domain adaptation[C]//2012 IEEE Conference on Computer Vision and Pattern Recognition. IEEE, 2012: 2066-2073.

If you have any questions, please open an issue.