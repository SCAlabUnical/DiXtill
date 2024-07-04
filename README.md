# XAI-driven Knowledge Distillation of Large Language Models for Efficient Deployment on Low-Resource Devices

## DiXtill: leveraging explanation alignment in teacher-student knowledge distillation
Our study introduces **DiXtill**, a novel approach to distilling explainable knowledge from an LLM into a lightweight, self-explainable neural architecture, leveraging local explanations to complement the usual prediction-based supervision. This overcomes the limitations of traditional distillation methods, which often fall short in transferring crucial explainable knowledge, leading to performance degradation and explanation inconsistencies.

Our experiments, involving the distillation of a pre-trained BERT-like model into an attention-enhanced bi-LSTM student, reveal that **DiXtill** enables the effective transfer of teacher explanations to the student, enhancing faithfulness and interpretability while maintaining performance. Moreover, the use of cross-architecture distillation allows for delivering a significantly higher compression ratio and speedup compared to compression techniques such as post-training quantization and attention head pruning.

These findings open avenues for more efficient and sustainable edge AI applications, empowering low-resource devices with the capabilities of Large Language Models without compromising performance and interoperability.

## How to run
This repository hosts all the code (Jupyter notebook) needed to run **DiXtill**. Additionally, a sample dataset is provided for demonstration purposes.</br>
>Before executing **DiXtill** download the *glove.6B.50d.txt* file from the official repository and extract it into the *data* folder. You can use the following command:
```bash
!wget http://nlp.stanford.edu/data/glove.6B.zip
```


## How to cite
*Cantini, R., Orsino, A., & Talia, D. (2024). Xai-driven knowledge distillation of large language models for efficient deployment on low-resource devices. Journal of Big Data, 11(1), 63.*

## Acknowledgements
This work has been partially supported by the *FAIR – Future Artificial Intelligence Research* project - CUP H23C22000860006.
