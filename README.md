# FiLMing-Multimodal-Sarcasm-Detection

This is the code for the paper:
#### FiLMing Multimodal Sarcasm Detection with Attention
*Sundesh Gupta, Aditya Shah, Miten Shah, Laribok Syiemlieh, Chandresh Maurya* <br>
To appear at ICONIP 2021

If you find this code useful in your research then please cite

``` 
@misc{gupta2021filming,
      title={FiLMing Multimodal Sarcasm Detection with Attention}, 
      author={Sundesh Gupta and Aditya Shah and Miten Shah and Laribok Syiemlieh and Chandresh Maurya},
      year={2021},
      eprint={2110.00416},
      archivePrefix={arXiv},
      primaryClass={cs.MM}
}
```

#### Code Outline

[film_roberta.ipynb](https://github.com/sundeshgupta/FiLMing-Multimodal-Sarcasm-Detection/blob/main/film_roberta.ipynb) implements the model proposed in the paper.

**To run the code:** 

1. Install the requirements `pip install -r requirements.txt`
2. If dataset is not downloaded or running for the first time, set the `DATA_READY` flag to false in the jupyter notebook. Running the code with the flag set to false will download the required datasets and put them into appropriate folders.
3. Run the jupyter notebok.

#### Dataset Description

We use the publicly available twitter multi-modal dataset. The dataset is also available [here](https://github.com/headacheboy/data-of-multimodal-sarcasm-detection).
