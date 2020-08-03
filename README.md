# Summarization Repository 
Authors: [Alex Fabbri*](http://alex-fabbri.github.io/), [Wojciech Kryściński*](https://twitter.com/iam_wkr), [Bryan McCann](https://bmccann.github.io/), [Caiming Xiong](http://cmxiong.com/), [Richard Socher](https://www.socher.org/), and [Dragomir Radev](http://www.cs.yale.edu/homes/radev/)<br/>

This project is a collaboration work between [Yale LILY Lab](https://yale-lily.github.io/) and [Salesforce Research](https://einstein.ai/). <br/><br/>

<p align="center">
<img src="assets/logo-lily.png" height="100" alt="LILY Logo" style="padding-right:160">
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;
<img src="assets/logo-salesforce.svg" height="100" alt="Salesforce Logo"> 
</p>

<sub><sup>\* - Equal contributions from authors</sup></sub>

## Table of Contents

1. [Updates](#updates)
2. [Data](#data)
3. [Evaluation Toolkit](#evaluation-toolkit)
4. [Citation](#citation)
5. [Get Involved](#get-involved)

## Updates
_7/16/2020_ - Initial commit! :) 

## Data
As part of this release, we share summaries generated by recent summarization model trained on the CNN/DailyMail dataset [here](#model-outputs).</br>
We also share human annotations, collected from both crowdsource workers and experts [here](#human-annotations).

Both datasets are shared WITHOUT the source articles that were used to generate the summaries. <br/>
To recreate the full dataset please follow the instructions listed [here](#data-preparation). 

### Model Outputs

|Model|Paper|Outputs|Type|
|-|-|-|-|
|M0|_Lead-3 Baseline_|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M0.tar.gz)|Extractive|
|M1|[Neural Document Summarization by Jointly Learning to Score and Select Sentences](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16838/16118)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M1.tar.gz)|Extractive|
|M2|[BANDITSUM: Extractive Summarization as a Contextual Bandit](http://aclweb.org/anthology/P18-1061)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M2.tar.gz)|Extractive|
|M3|[Neural Latent Extractive Document Summarization](http://aclweb.org/anthology/D18-1088)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M3.tar.gz)|Extractive|
|M4|[Ranking Sentences for Extractive Summarization with Reinforcement Learning](https://www.aclweb.org/anthology/N18-1158/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M4.tar.gz)|Extractive|
|M5|[Learning to Extract Coherent Summary via Deep Reinforcement Learning](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16838/16118)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M5.tar.gz)|Extractive|
|M6|[Neural Extractive Text Summarization with Syntactic Compression](https://www.aclweb.org/anthology/D19-1324/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M6.tar.gz)|Extractive|
|M7|[STRASS: A Light and Effective Method for Extractive Summarization Based on Sentence Embeddings](https://www.aclweb.org/anthology/P19-2034/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M7.tar.gz)|Extractive|
|M8|[Get To The Point: Summarization with Pointer-Generator Networks](http://aclweb.org/anthology/P17-1099)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M8.tar.gz)|Abstractive|
|M9|[Fast Abstractive Summarization with Reinforce-Selected Sentence Rewriting](https://www.aclweb.org/anthology/P18-1063)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M9.tar.gz)|Abstractive|
|M10|[Bottom-Up Abstractive Summarization](https://www.aclweb.org/anthology/D18-1443/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M10.tar.gz)|Abstractive|
|M11|[Improving Abstraction in Text Summarization](http://aclweb.org/anthology/D18-1207)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M11.tar.gz)|Abstractive|
|M12|[A Unified Model for Extractive and Abstractive Summarization using Inconsistency Loss](http://aclweb.org/anthology/P18-1013)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M12.tar.gz)|Abstractive|
|M13|[Multi-Reward Reinforced Summarization with Saliency and Entailment](http://aclweb.org/anthology/N18-2102)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M13.tar.gz)|Abstractive|
|M14|[Soft Layer-Specific Multi-Task Summarization with Entailment and Question Generation](http://aclweb.org/anthology/P18-1064)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M14.tar.gz)|Abstractive|
|M15|[Closed-Book Training to Improve Summarization Encoder Memory](http://aclweb.org/anthology/D18-1440)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M15.tar.gz)|Abstractive|
|M16|[An Entity-Driven Framework for Abstractive Summarization](https://www.aclweb.org/anthology/D19-1323/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M16.tar.gz)|Abstractive|
|M17|[Exploring the Limits of Transfer Learning with a Unified Text-to-Text Transformer](https://arxiv.org/abs/1910.10683)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M17.tar.gz)|Abstractive|
|M18|[Better Rewards Yield Better Summaries: Learning to Summarise Without References](https://www.aclweb.org/anthology/D19-1307)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M18.tar.gz)|Abstractive|
|M19|[Text Summarization with Pretrained Encoders](https://www.aclweb.org/anthology/D19-1387)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M19.tar.gz)|Abstractive|
|M20|[Fine-Tuning GPT-2 from Human Preferences](https://openai.com/blog/fine-tuning-gpt-2/)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M20.tar.gz)|Abstractive|
|M21|[Unified Language Model Pre-training for Natural Language Understanding and Generation](https://arxiv.org/abs/1905.03197)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M21.tar.gz)|Abstractive|
|M22|[BART: Denoising Sequence-to-Sequence Pre-training for Natural Language Generation, Translation, and Comprehension](https://www.aclweb.org/anthology/2020.acl-main.703)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M22.tar.gz)|Abstractive|
|M23|[PEGASUS: Pre-training with Extracted Gap-sentences for Abstractive Summarization](https://arxiv.org/pdf/1912.08777.pdf)|[Link](https://storage.googleapis.com/sfr-summarization-repo-research/M23.tar.gz)|Abstractive|

**IMPORTANT:** 

All model outputs were obtained from the original authors of the models and shared with their consent.<br/>
When using any of the model outputs, please also _cite the original paper_.


### Human annotations

Human annotations of model generated summaries can be found [here](https://storage.googleapis.com/sfr-summarization-repo-research/model_annotations.aligned.jsonl).

The annotations include summaries generated by 16 models from 100 source news articles (1600 examples in total). <br/>
Each of the summaries was annotated by 5 indepedent crowdsource workers and 3 independent experts (8 annotations in total). <br/>
Summaries were evaluated across 4 dimensions: _coherence_, _consistency_, _fluency_, _relevance_. <br/>
Each source news article comes with the original reference from the CNN/DailyMail dataset and 10 additional crowdsources reference summaries.

### Data preparation

Both model generated outputs and human annotated data require pairing with the original CNN/DailyMail articles.

To recreate the datasets follow the instructions:
1. Download CNN Stories and Daily Mail Stories from https://cs.nyu.edu/~kcho/DMQA/
2. Create a `cnndm` directory and unpack downloaded files into the directory
3. Download and unpack model outputs or human annotations.
4. Run the `pair_data.py` script to pair the data with original articles

Example call for _model outputs_:

`python3 data_processing/pair_data.py --model_outputs <file-with-data-annotations> --story_files <dir-with-stories>`

Example call for _human annotations_:

`python3 data_processing/pair_data.py --data_annotations <file-with-data-annotations> --story_files <dir-with-stories>`


## Evaluation Toolkit

We provide a toolkit for summarization evaluation to unify metrics and promote robust comparison of summarization systems. The toolkit contains popular and recent metrics for summarization as well as several machine translation metrics.

### Metrics ###
Below are the metrics included in the tookit, followed by the associated paper and code used within the toolkit:
|Metric|Paper|Code|
|-|-|-|
|ROUGE|[ROUGE: A Package for Automatic Evaluation of Summaries](https://www.aclweb.org/anthology/W04-1013.pdf)|[Link](https://github.com/bheinzerling/pyrouge/tree/master/pyrouge)|
|ROUGE-we|[Better Summarization Evaluation with Word Embeddings for ROUGE](https://www.aclweb.org/anthology/D15-1222.pdf)|[Link](https://github.com/UKPLab/emnlp-ws-2017-s3/blob/master/S3/ROUGE.py#L152)|
|MoverScore|[MoverScore: Text Generation Evaluating with Contextualized Embeddings and Earth Mover Distance](https://www.aclweb.org/anthology/D19-1053.pdf)|[Link](https://github.com/AIPHES/emnlp19-moverscore/)|
|BertScore|[BertScore: Evaluating Text Generation with BERT](https://arxiv.org/pdf/1904.09675.pdf)|[Link](https://github.com/Tiiiger/bert_score)|
|Sentence Mover's Similarity|[Sentence Mover’s Similarity: Automatic Evaluation for Multi-Sentence Texts](https://www.aclweb.org/anthology/P19-1264.pdf)|[Link](https://github.com/eaclark07/sms)|
|SummaQA|[Answers Unite! Unsupervised Metrics for Reinforced Summarization Models](https://www.aclweb.org/anthology/D19-1320.pdf)|[Link](https://github.com/recitalAI/summa-qa)|
|METEOR|[METEOR: An Automatic Metric for MT Evaluation with Improved Correlation with Human Judgments ](https://www.aclweb.org/anthology/W05-0909.pdf)|[Link](https://github.com/Maluuba/nlg-eval/tree/master/nlgeval/pycocoevalcap/meteor)|
|S<sup>3</sup>|[Learning to Score System Summaries for Better Content Selection Evaluation](https://www.aclweb.org/anthology/W17-4510/)|[Link](https://github.com/UKPLab/emnlp-ws-2017-s3)|
|Misc. statistics<br/>(extractiveness, novel n-grams, repetition, length)|[Newsroom: A Dataset of 1.3 Million Summaries with Diverse Extractive Strategies](https://www.aclweb.org/anthology/N18-1065/)| [Link](https://github.com/lil-lab/newsroom)|
|Syntactic Evaluation|[Automatic Analysis of Syntactic Complexity in Second Language writing](https://www.benjamins.com/catalog/ijcl.15.4.02lu)|[Link](http://www.personal.psu.edu/xxl13/downloads/L2SCA-2016-06-30.tgz)|
|CIDer|[CIDEr: Consensus-based Image Description Evaluation](https://www.cv-foundation.org/openaccess/content_cvpr_2015/papers/Vedantam_CIDEr_Consensus-Based_Image_2015_CVPR_paper.pdf)|[Link](https://github.com/Maluuba/nlg-eval/tree/master/nlgeval/pycocoevalcap/cider)|
|CHRF|[CHRF++: words helping character n-grams](https://www.statmt.org/wmt17/pdf/WMT70.pdf)|[Link](https://github.com/m-popovic/chrF)|
|BLEU|[BLEU: a Method for Automatic Evaluation of Machine Translation](https://www.aclweb.org/anthology/P02-1040.pdf)|[Link](https://github.com/mjpost/sacreBLEU)|


#### SETUP ####

First install the summ_eval toolkit:
```bash
git clone https://github.com/Yale-LILY/summarization-repository.git
cd evaluation
pip install -e .
```

To finish the setup, please run and follow the prompts in this script:

```
python setup_finalize.py
```

You can test your installation and get familiar with the library through `tests/`

```
python -m unittest discover
```


### Command-line interface
We provide a command-line interface `calc-scores` which makes use of [gin config](https://github.com/google/gin-config) files to set metric parameters. 

##### Examples
Run ROUGE on given source and target files and write to `rouge.jsonl`, analogous to [files2rouge](https://github.com/pltrdy/files2rouge). 
```
calc-scores --config-file=examples/basic.config --metrics "rouge" --summ-file summ_eval/1.summ --ref-file summ_eval/1.ref --output-file rouge.jsonl --eos " . " --aggregate True
```

**NOTE**: if you're seeing slow-ish startup time, try commenting out the metrics you're not using in the config; otherwise this will load all modules. 


Run ROUGE and BertScore on a jsonl file which contains "reference" and "summary" keys and write to `output.jsonl`. 
```
calc-scores --config-file=examples/basic.config --metrics "rouge, bert_score" --jsonl-file data.jsonl --output-file rouge_bertscore.jsonl
```

For a full list of options, please run:
```
calc-scores --help
```


### For use in scripts
If you want to use the evaluation metrics as part of other scripts, we have you covered!

```
from summ_eval.rouge_metric import RougeMetric
rouge = RougeMetric()
```

#### Evaluate on a batch
```
summaries = ["This is one summary", "This is another summary"]
references = ["This is one reference", "This is another"]

rouge_dict = rouge.evaluate_batch(summaries, references)
```

#### Evaluate on a single example
```
rouge_dict = rouge.evaluate_example(summaries[0], references[0])
```


#### Evaluate with multiple references
Currently the command-line tool does not use multiple references for simplicity. Each metric has a `supports_multi_ref` property to tell you if it supports multiple references. 

```
print(rouge.supports_multi_ref) # True
multi_references = [["This is ref 1 for summ 1", "This is ref 2 for summ 1"], ["This is ref 1 for summ 2", "This is ref 2 for summ 2"]]
rouge_dict = rouge.evaluate_batch(summaries, multi_references)
```





## Citation

```
@article{fabbri2020summeval,
  title={SummEval: Re-evaluating Summarization Evaluation},
  author={Fabbri, Alexander R and Kry{\'s}ci{\'n}ski, Wojciech and McCann, Bryan and Xiong, Caiming and Socher, Richard and Radev, Dragomir},
  journal={arXiv preprint arXiv:2007.12626},
  year={2020}
}
```

### Get Involved

Please create a GitHub issue if you have any questions, suggestions, requests or bug-reports. 
We welcome PRs!
