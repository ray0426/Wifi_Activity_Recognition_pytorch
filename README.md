# Wi-fi-Activity-recognition-Pytorch-Rewrite
This is a pytorch version of <a href="https://github.com/ermongroup/Wifi_Activity_Recognition">Wifi_Activity_Recognition</a> by ermongroup.

## Environment

GPU: NVIDIA GPU

OS: Windows 10 (linux might also be okay)

Package Management: conda 4.12.0 (conda is Highly recommend. Other version of conda might also be okay)

## Prerequisite

```
python==3.11.8
pytorch==2.2.1
numpy
tqdm
pandas
jupyter
```
You can install pytorch by the script described in <a href="https://pytorch.org/get-started/locally/">pytorch start locally</a>.

You can install other packages (except pytorch related) by `pip install numpy tqdm pandas jupyter` after pytorch installed.

<br/>

## How to  run
0. Download dataset from [here](https://drive.google.com/file/d/1OA8pb_KWjFV2Vh2ymOvvQ2zJrp5GhmI-/view?usp=sharing)
 -> **Notice: Dataset size is ~4GB**

1. `git clone` this repository.
 
2. Run the `main.ipynb`
 -> This notebook process the data and run the training code. You can run each block separately

## Other information
Plese check original repo [here](https://github.com/ermongroup/Wifi_Activity_Recognition)
