## indian-english-asr

### How to train ASR model on custom data
##### Training/Finetuning using Nvidia's TAO
- Speech to Text training [reference](https://docs.nvidia.com/tao/tao-toolkit/text/asr/speech_recognition_with_conformer.html)
  
##### Training/Finetuning using Nvidia's NeMo
- Conformer SSL [reference](https://catalog.ngc.nvidia.com/orgs/nvidia/teams/nemo/models/ssl_en_conformer_large)
  
### Model
- [Conformer-CTC](https://docs.nvidia.com/deeplearning/nemo/user-guide/docs/en/stable/asr/models.html#conformer-ctc)

### Checkpoints
|   Language   | Checkpoint | WER |
|--------------|------------|-----|
|Indian-English|  [link]()  |18.17|  

WER evaulated using NPTEL-Pure-Dataset (later will include other dataset)
    
### Training Dataset
- Download data from [NPTEL2020 - Indian English Speech Dataset](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset)
  
| Dataset | GroundTruth | AudioFiles | Min duration | Max duration | Total Hours | 
|---------|-------------|------------|--------------|--------------|-------------|
|  Train  |             |            |              |              |             |
|  Valid  |   624968    |   624968   |     0sec     |     16sec    |   1295.84   |
|  Test   |   625152    |   625152   |     0sec     |              |   1335.74   |

### Benchmarking 
- [Svarah : An Indic accented English speech dataset](https://github.com/AI4Bharat/Svarah/tree/master)
- NPTEL-Pure Dataset
  
### References
- [NPTEL2020 - Indian English Speech Dataset](https://github.com/AI4Bharat/NPTEL2020-Indian-English-Speech-Dataset)
- [Svarah : An Indic accented English speech dataset](https://github.com/AI4Bharat/Svarah/tree/master)
- [Nvidia-Tao](https://github.com/NVIDIA-AI-IOT/nvidia-tao)
