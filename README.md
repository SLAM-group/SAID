<p align="center" width="60%">
<a ><img src="assets/said_logo_2.png" alt="SAID-logo" style="width: 60%; margin: auto;"></a>
</p>

# SAID: A Benchmark For Social Media AI Detection.

This is the repository for [Who Said That? Benchmarking Social Media
AI Detection](https://openreview.net/attachment?id=THtX863Io2&name=pdf)

## <a id="overview"></a>Overview

We create novel benchmark **SAID**(**S**ocial media **AI** **D**etection) for social media AI detection. Unlike existing benchmarks, it incorporates real AI-generate text from popular social media platforms like Zhihu and Quora, and deals with content that reflects the sophisticated strategies employed by real AI users on the Internet which may evade detection or gain visibility, providing a more realistic and challenging evaluation landscape. 

# Dataset Info

## SAID-Quora and SAID-Zhihu

For original SAID_zhihu dataset, you can download from [here](https://drive.google.com/drive/folders/1M2SwWS68kRnN36dkbTgxLvFWUjZqnRz7).

For original SAID_quora dataset, you can download from [here](https://drive.google.com/drive/folders/1A6er-AoQ0iZJGCq1KSvutB0pFWMUR9Zm).

The statistics of those two datasets are shown below

<p align="center" width="50%">
<a ><img src="assets/table 1.png" alt="Ada-Instruct" style="width: 70%; margin: auto;"></a>
</p>

### Example of zhihu ai

| question                      | answer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                   |
|-------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 六个月控制工程考研可以上岸吗? | 首先，我要提醒你的是，控制工程是一门非常复杂的学科，需要很强的数学基础和抽象思维能力。如果你没有接受过相关课程或者没有充分的准备，六个月的时间内想要考上控制工程研究生可能会有些困难。 其次，考上控制工程研究生需要具备一定的竞争力，包括综合素质和学术能力。因此，在考研前需要做好充分的准备，包括针对考试科目的系统学习和复习，同时提高自身的英语水平，扩大学术视野，积累相关的科研或实习经验等。 最后，211双一流院校对于控制工程的研究生招生要求比较高，需要综合各方面因素进行评估。你可以了解一下各个高校的招生信息和录取标准，根据自身情况选择适合自己的学校和专业。 总之，如果你有充足的准备并且真心喜欢控制工程这个学科，那么六个月内考上研究生是有可能的。但是，要想取得更好的成绩和更好的前途，需要更长时间的努力和持续的学习。 |

### Example of zhihu human

### Example of quora ai

### Example of quora human

## Train set and Test set 

The train and test dataset are composed from detector features extracted by different detectors on original SAID subset. For example, SAID_quora_train is the training set on quora extracted by different detectors([SimpleAI](https://huggingface.co/Hello-SimpleAI), [MPU](https://xihe.mindspore.cn/modelzoo/text-detector), [GPT-Zero](https://gptzero.me/)), and SAID_quora_test is the test set on quora converted by those three detectors.

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
