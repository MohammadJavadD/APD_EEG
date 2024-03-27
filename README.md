# APD_EEG
Code for "[Amplifying pathological detection in EEG signaling pathways through cross-dataset transfer learning](https://www.sciencedirect.com/science/article/pii/S0010482523013586)"

# Setup the environment
```bash
conda env create -f environment.yaml

# Activate the environment
conda activate APD_EEG
```
# Run the Jupyter notebooks
First run `s1_data_prepapration.ipynb` to prepare the data, then run `s2_supervised_learning.ipynb` to train the model, and finally run `s3_transfer_learning.ipynb` to finetune the model.

# Citation
If you find this code useful, please cite our paper:
```
@article{darvishi2024amplifying,
  title={Amplifying pathological detection in EEG signaling pathways through cross-dataset transfer learning},
  author={Darvishi-Bayazi, Mohammad-Javad and Ghaemi, Mohammad Sajjad and Lesort, Timothee and Arefin, Md Rifat and Faubert, Jocelyn and Rish, Irina},
  journal={Computers in Biology and Medicine},
  volume={169},
  pages={107893},
  year={2024},
  publisher={Elsevier}
}
```