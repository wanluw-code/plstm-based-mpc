# Phased LSTM based MPC for modeling and control of nonlinear systems with asynchronous and delayed measurements
This project demonstrates how the Phased LSTM model (PLSTM) proposed by Neil et al. [1] can be used to model two chemical processes that are subjected to asynchronity and delay in their sensor measurements:

- Case Study 1: Extractive Dividing Wall Column (EDWC)
- Case Study 2: A single continuous stirred tank reactor (CSTR)

## Prerequisites
- Python 3.8 or higher
### Install Dependencies
Install the required Python packages:
```bash
pip install scikit-learn==1.5.1 numpy==1.26.4 torch==2.3.1 torchvision==0.18.1 torchaudio==2.3.1 matplotlib==3.9.1
```

## Acknowledgments
The plstm_cell.py code was modified based on the original code provided in:
- [pytorch_plstm](https://github.com/dannyneil/pytorch_plstm) by [dannyneil](https://github.com/dannyneil)

## References
[1] D. Neil, M. Pfeiffer, and S. C. Liu, “Phased lstm: Accelerating recurrent network training for long or event-based sequences,” _Advances in
Neural Information Processing Systems_, vol. 29, 2016.

