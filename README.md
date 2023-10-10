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
| 六个月控制工程考研可以上岸吗? | **首先**，我要提醒你的是，控制工程是一门非常复杂的学科，需要很强的数学基础和抽象思维能力。如果你没有接受过相关课程或者没有充分的准备，六个月的时间内想要考上控制工程研究生可能会有些困难。 <br/> **其次**，考上控制工程研究生需要具备一定的竞争力，包括综合素质和学术能力。因此，在考研前需要做好充分的准备，包括针对考试科目的系统学习和复习，同时提高自身的英语水平，扩大学术视野，积累相关的科研或实习经验等。<br/> **最后**，211双一流院校对于控制工程的研究生招生要求比较高，需要综合各方面因素进行评估。你可以了解一下各个高校的招生信息和录取标准，根据自身情况选择适合自己的学校和专业。<br/> **总之**，如果你有充足的准备并且真心喜欢控制工程这个学科，那么六个月内考上研究生是有可能的。但是，要想取得更好的成绩和更好的前途，需要更长时间的努力和持续的学习。 |

### Example of zhihu human

| question                         | answer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
|----------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 你有哪些当初没听出来的弦外之音？ | 升初二的暑假，一天下午外面淅淅沥沥，下起了不大不小的中雨。暗恋已久的女生借请教电脑操作问题给我讲，下雨天想吃麻辣烫，正好是我家和她家中间那家的，我说我也想吃！她问我要不要去买一个，但是外面正在下雨。我说没问题，这点雨我不穿雨衣都没问题的，我去就好了，你在家等我。 <br/>  落汤鸡进去麻辣烫店，打包2份麻辣烫。 落汤鸡骑车到她家楼下，给她打电话她慌忙下来迎接我，问我要不要上去坐坐？我问她家里没人？她说有一位女同学，但是马上要补课走人了。我说好，那你们在吧，有外人我会尴尬，而且我的麻辣烫只有在我家吃着才香。 落汤鸡又淋了20分钟到自己家楼下，看着被雨水浸湿的自己和冰冷的麻辣烫，愤怒的给了自己一个巴掌。 |

### Example of quora ai

| question                                                       | answer                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                        |
|----------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Which algorithm is best suitable for studying protein folding? | The study of protein folding **is a complex problem** in structural biology, and there is no single algorithm that is universally considered the "best" for studying protein folding. However, there are several prominent algorithms and approaches that have been successfully used in protein folding research. **Here are** a few notable examples: <br/>  **1. Molecular Dynamics (MD)**: Molecular Dynamics simulations simulate the physical movements of atoms and molecules over time. MD simulations can provide valuable insights into the dynamics and folding pathways of proteins. Advanced MD techniques, such as Replica Exchange Molecular Dynamics (REMD) and Accelerated Molecular Dynamics (AMD), have been employed to enhance sampling and explore folding landscapes. <br/>  **2. Monte Carlo (MC) Methods**: Monte Carlo methods use random sampling techniques to explore the conformational space of proteins. In the context of protein folding, techniques like Monte Carlo with Minimization (MCM) and Parallel Tempering Monte Carlo (PTMC) have been employed to sample and search for low-energy conformations. <br/>  **3. Coarse-Grained Modeling**: Coarse-grained models simplify the representation of proteins by reducing the level of detail, typically by grouping several amino acids into a single "bead." Coarse-grained models enable researchers to simulate longer timescales and larger systems, facilitating the study of protein folding dynamics. Popular coarse-grained models include the Go model and the Cα-based models. <br/>  **4. Fragment Assembly**: Fragment assembly methods break down the protein folding problem into smaller fragments, which are then reassembled to generate full protein structures. This approach combines both experimental data and computational techniques to predict protein structures. Examples of fragment assembly methods include Rosetta and QUARK. <br/>  **5. Machine Learning (ML) Approaches**: Machine learning techniques, such as deep learning and reinforcement learning, have been applied to predict and simulate protein folding. These methods leverage large datasets and powerful neural networks to learn patterns and correlations in protein folding. AlphaFold, developed by DeepMind, is a notable example that achieved remarkable success in protein structure prediction by utilizing deep learning. <br/>  **It's worth noting that** different algorithms and approaches have their own strengths, limitations, and areas of applicability.  |

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
