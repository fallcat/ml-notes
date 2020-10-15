# Issues when running different existing codebases

## XLM
Need to use gcc7
Make sure cuda version is the same as the cuda that is used to compile pytorch!

## Unsupervised QA
pip uninstall msgpack-python
pip install msgpack==0.6.2
pip install scikit-learn==0.22.2
conda install -c omnia cuda92

RuntimeError: CuDNN error: CUDNN_STATUS_SUCCESS
conda install pytorch=0.4.1 cuda92 -c pytorch
Need to have pytorch have same coda version as coda
