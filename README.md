# DS202 / Data science thesis 1

## About

* This is a college course project about collecting social data from Internet for for NLP emotion classification task.
* Techniques applied:
> * Data collection and cleaning
> * Annotation guildlines
> * Word tokenization, Deep learning models

## Table of contents

> * [DS200.L21 / Big data](#ds202--data-science-thesis-1)
* [About](#about)
* [Table of contents](#table-of-contents)
* [Data source](#data-source)
* [Experiment pipelines](#experiment-pipelines)
* [Data details](#data-details)
* [Code](#code)
* [Presentation slides and Report](#presentation-slides-and-report)
* [References](#references)
* [Cite us](#cite-us)

## Data source

* <a href="https://github.com/githubbinh/DS202_Data-Science-thesis-1/tree/main/raw_data" target="_blank">Raw data</a>
* <a href="https://github.com/githubbinh/DS202_Data-Science-thesis-1/tree/main/processed_data" target="_blank">Clean data</a>


## Experiment pipelines
![](images/pipelines.png)

## Data details
* Label distribution

![](images/datainfo.png)

* Word count

![](images/word_count.png)

* Comment length distribution over labels

![](images/lenghtbylabel.png)

* Annotation agreement results over 5 rounds

![](images/anno_agreement.png)

## Code

* Feature extraction and models training (and so on) in this repo are implemented in Google Colab.
* All codes are organized in `name.ipynb` files.

## Presentation slides and Report

* <a href="https://github.com/githubbinh/DS202_Data-Science-thesis-1/blob/main/slides_UITVLFC.pptx" target="_blank">Report slides</a>
* <a href="https://github.com/githubbinh/DS202_Data-Science-thesis-1/blob/main/report_UIT-VLFC.pdf" target="_blank">Report</a>
* <a href="https://github.com/githubbinh/DS202_Data-Science-thesis-1/blob/main/guildlines_UITVLFC.pdf" target="_blank">Guildlines</a>

## References

* All references are cited in the report file.

## Cite us
```
@INPROCEEDINGS{9997964,
  author={Van Duong, Binh and Nguyen, An Trong and Ha, Chien Nhu and Duong, Hong-Hanh Thi and Tran, My-Linh Thi and Do, Trong-Hop},
  booktitle={2022 25th Conference of the Oriental COCOSDA International Committee for the Co-ordination and Standardisation of Speech Databases and Assessment Techniques (O-COCOSDA)}, 
  title={UIT-VLFC: Vietnamese Lipstick Feedbacks Corpus}, 
  year={2022},
  volume={},
  number={},
  pages={1-5},
  doi={10.1109/O-COCOSDA202257103.2022.9997964}}
```
