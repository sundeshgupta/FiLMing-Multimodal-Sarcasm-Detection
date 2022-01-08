# FiLMing-Multimodal-Sarcasm-Detection

This repo contains code for the paper:
### [FiLMing Multimodal Sarcasm Detection with Attention](https://arxiv.org/abs/2110.00416)
*Sundesh Gupta, Aditya Shah, Miten Shah, Laribok Syiemlieh, Chandresh Maurya* <br>
In the Proceedings of the <i>28th International Conference on Neural Information Processing (ICONIP 2021)</i>

If you find this code useful in your research then please cite
``` 
@InProceedings{10.1007/978-3-030-92307-5_21,
author="Gupta, Sundesh and Shah, Aditya and Shah, Miten and Syiemlieh, Laribok and Maurya, Chandresh",
editor="Mantoro, Teddy and Lee, Minho and Ayu, Media Anugerah and Wong, Kok Wai and Hidayanto, Achmad Nizar",
title="FiLMing Multimodal Sarcasm Detection with Attention",
booktitle="Neural Information Processing",
year="2021",
publisher="Springer International Publishing",
pages="178--186",
isbn="978-3-030-92307-5"
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
