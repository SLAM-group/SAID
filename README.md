# SAID
A Benchmark For Social Media AI Detection. [Who Said That? Benchmarking Social Media
AI Detection](https://openreview.net/attachment?id=THtX863Io2&name=pdf)

We create datasets for social media AI detection, and upload the train and test set for this repo. The train and test dataset are composed from detector features.

The responses pair for human identifyting experiment in Table 3 is given in pairs_zhihu.xlsx

For SAID_zhihu dataset, you can download from [here](https://drive.google.com/drive/folders/1M2SwWS68kRnN36dkbTgxLvFWUjZqnRz7).

For SAID_quora dataset, you can download from [here](https://drive.google.com/drive/folders/1A6er-AoQ0iZJGCq1KSvutB0pFWMUR9Zm).


We test three different detectors, and show the results below:

<p align="center" width="100%">
<a ><img src="assets/table 5.png" alt="Ada-Instruct" style="width: 100%; margin: auto;"></a>
</p>

### Performance of Different AI Detectors on SAID and HC3. 

|               | SAID-zhihu |           |        |            | SAID-quora |           |        |             | HC3  |
|---------------|:----------:|:---------:|:------:|:----------:|:----------:|:---------:|:------:|:-----------:|------|
|               | accuracy   | precision | recall | f1         | accuracy   | precision | recall | f1          | f1   |
| HelloSimpleAI | 96.1       | 97.6      | 96.4   | 96.7(+0.3) | 84.4       | 84.1      | 79.8   | 81.9(-14.5) | 96.4 |
| GPT-Zero      |      -     |     -     |    -   |      -     | 89.1       | 97        | 81.3   | 88.5        |   -  |
| MPU           | 93.9       | 97.1      | 92.3   | 94.7(-3.7) | 89.3       | 96        | 74.7   | 84(-14.4)   | 98.4 |

## Citation

If you find this codebase useful in your research, please cite the following paper.
```
@article{
    // To be done
}
