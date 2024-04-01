See our Pathology Detector space at:

.. image:: https://huggingface.co/datasets/huggingface/brand-assets/resolve/main/hf-logo-with-title.svg?style=svg
   :target: https://huggingface.co/spaces/MJ/EEG_cls
   :alt:  View on Hugging Face 🤗 Spaces
   :width: 200px 

Or run the code in Binder:

.. image:: https://mybinder.org/badge_logo.svg?style=svg
 :target: https://mybinder.org/v2/gh/MohammadJavadD/APD_EEG/HEAD

APD EEG
========
Code for "`Amplifying pathological detection in EEG signaling pathways through cross-dataset transfer learning <https://www.sciencedirect.com/science/article/pii/S0010482523013586>`_"


Run the Jupyter notebooks
-------------------------
You only need to open and run the following Jupyter notebooks in order. No need for setup or downoad any datasets. We use a mock version of TUAB and NMT for these notebooks, however the code to download these dataets is also available in the first notebook. 

1. Run "`s1_data_preparation.ipynb <https://github.com/MohammadJavadD/APD_EEG/blob/main/s1_data_preparation.ipynb>`_" to prepare the data.
2. Run "`s2_supervised_learning.ipynb <https://github.com/MohammadJavadD/APD_EEG/blob/main/s2_supervised_learning.ipynb>`_" to train the model.
3. Run "`s3_transfer_learning.ipynb <https://github.com/MohammadJavadD/APD_EEG/blob/main/s3_transfer_learning.ipynb>`_" to fine-tune the model.

If you want to create an enviroment to run the code, you can use the following command:

Setup the environment
---------------------
You can create a new environment using the provided `environment.yaml` file.
.. code-block:: bash

   conda env create -f environment.yaml

   # Activate the environment
   conda activate APD_EEG

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
