# SAID

# <div align="center">A Benchmark For Social Media AI Detection. </div>

<p align="center" width="30%">
<a ><img src="assets/said_logo.png" alt="SAID-logo" style="width: 30%; margin: auto;"></a>
</p>

This is the repository for [Who Said That? Benchmarking Social Media
AI Detection](https://openreview.net/attachment?id=THtX863Io2&name=pdf)

## <a id="overview"></a>Overview

We create novel benchmark **SAID**(**S**ocial media **AI** **D**etection) for social media AI detection. Unlike existing benchmarks, it incorporates real AI-generate text from popular social media platforms like Zhihu and Quora, and deals with content that reflects the sophisticated strategies employed by real AI users on the Internet which may evade detection or gain visibility, providing a more realistic and challenging evaluation landscape. 

# Dataset Info

## SAID-Quora and SAID-Zhihu

For original SAID_zhihu dataset, you can download from [here](https://drive.google.com/drive/folders/1M2SwWS68kRnN36dkbTgxLvFWUjZqnRz7).

For original SAID_quora dataset, you can download from [here](https://drive.google.com/drive/folders/1A6er-AoQ0iZJGCq1KSvutB0pFWMUR9Zm).

The statistics of those two datasets are shown below, we remove the duplicate question-answer pairs. Thus the statistics is a little bit different from table 1 of [SAID paper](https://openreview.net/attachment?id=THtX863Io2&name=pdf).

<p align="center" width="50%">
<a ><img src="assets/table 1.png" alt="Ada-Instruct" style="width: 70%; margin: auto;"></a>
</p>

## Train set and Test set 

The train and test dataset are composed from detector features extracted by different detectors on original SAID dataset. For example, SAID_quora_train is the training set on quora extracted by different detectors([SimpleAI](https://huggingface.co/Hello-SimpleAI), [MPU](https://xihe.mindspore.cn/modelzoo/text-detector), [GPT-Zero](https://gptzero.me/)), and SAID_quora_test is the test set on quora converted by those three detectors.

## Responses pairs for human identification

The responses pairs for human identification experiment in Table 3 are given in [pairs_zhihu](https://github.com/SLAM-group/SAID/blob/main/pairs_zhihu.xlsx). The human evaluation results are shown below:

<p align="center" width="70%">
<a ><img src="assets/table 3.png" alt="Ada-Instruct" style="width: 70%; margin: auto;"></a>
</p>

## Evaluation of prevalent detectors on SAID

We test three different detectors, and show the results below:

<p align="center" width="100%">
<a ><img src="assets/table 5.png" alt="Ada-Instruct" style="width: 100%; margin: auto;"></a>
</p>

# Citation

If you find this codebase useful in your research, please cite the following paper.
```
@article{
    // To be done
}
