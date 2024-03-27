.. image:: https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo-with-title.svg?style=svg
   :target: https://huggingface.co/spaces/MJ/EEG_cls
   :alt:  View on Hugging Face 🤗 Spaces
   :width: 10% 

APD_EEG
========
Code for "`Amplifying pathological detection in EEG signaling pathways through cross-dataset transfer learning <https://www.sciencedirect.com/science/article/pii/S0010482523013586>`_"

Setup the environment
---------------------
.. code-block:: bash

   conda env create -f environment.yaml

   # Activate the environment
   conda activate APD_EEG

Run the Jupyter notebooks
-------------------------
1. Run ``s1_data_preparation.ipynb`` to prepare the data.
2. Run ``s2_supervised_learning.ipynb`` to train the model.
3. Run ``s3_transfer_learning.ipynb`` to fine-tune the model.

Citation
--------
If you find this code useful, please cite our paper:

.. code-block:: bibtex

   @article{darvishi2024amplifying,
     title={Amplifying pathological detection in EEG signaling pathways through cross-dataset transfer learning},
     author={Darvishi-Bayazi, Mohammad-Javad and Ghaemi, Mohammad Sajjad and Lesort, Timothee and Arefin, Md Rifat and Faubert, Jocelyn and Rish, Irina},
     journal={Computers in Biology and Medicine},
     volume={169},
     pages={107893},
     year={2024},
     publisher={Elsevier}
   }
