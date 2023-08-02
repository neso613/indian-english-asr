## indian-english-asr

### How to train ASR model on custom data
##### Train/Finetuning using TAO
- Speech to Text training [reference](https://docs.nvidia.com/tao/tao-toolkit/text/asr/speech_recognition_with_conformer.html)
  
### Model
- [Conformer-CTC](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/stable/asr/models.html#conformer-ctc)
    
### Training Dataset
- Download data from [NPTEL2020 - Indian English Speech Dataset](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset)
  
| Dataset | GroundTruth | AudioFiles | Min duration | Max duration | Total Hours | 
|---------|-------------|------------|--------------|--------------|-------------|
|  Train  |             |            |              |              |             |
|  Valid  |   624968    |   624968   |     0sec     |     16sec    |  1235 hours |
|  Test   |   625152    |   625152   |              |              |             |

### Benchmarking Dataset
- [Svarah : An Indic accented English speech dataset](https://github.com/AI4Bharat/Svarah/tree/master)
- NPTEL-Pure Dataset
  
### References
- [NPTEL2020 - Indian English Speech Dataset](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset)
- [Svarah : An Indic accented English speech dataset](https://github.com/AI4Bharat/Svarah/tree/master)
- [Nvidia-Tao](https://github.com/NVIDIA-AI-IOT/nvidia-tao)
