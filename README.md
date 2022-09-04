# Tempo

This is the Pytorch implementation of TEMPO in the paper: [TEMPO: A Transformer-based Mutation Prediction Framework for SARS-CoV-2 Evolution] .

## Requirements
- pytorch
- sklearn

## Usage
To run the code
1. Download data: data.zip shuold be downloaded **separately**， you can [click here](https://github.com/ZJUDataIntelligence/Tempo/raw/main/data.zip) to download the data.
2. cd to *data* folder:
`unzip data.zip`
3. you may need to chage the dataset path defined in training.py(Corresponds to your *data* directory)
4. cd to project root folder:
`python training.py`
