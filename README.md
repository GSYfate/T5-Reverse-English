# Implementation of a Fine-Tuned T5 Model for English to Reverse-English
This project presents an implementation of a fine-tuned T5 model, designed to transform standard English sentences into their reversed counterparts. The model is trained to take sentences from newspaper articles and then transform these sentences into reversed English versions. 

## Model
[T5-base](https://huggingface.co/t5-base)

## Dataset
[ag_news](https://huggingface.co/datasets/ag_news)

## Training
`bash train.sh`

## Results
Below are two examples of the model's output after fine-tuning.

**Example1**

Original Text

`Running Extra Mile Sets Humans Apart in Primates'World The ability of early human ancestors to run`

Generated Text

`nur ot srotsecna namuh ylrae fo ytiliba ehT dlroW'setamirP ni trapA snamuH steS eliM artxE gninnuR`

Actual Reverse Text

`nur ot srotsecna namuh ylrae fo ytiliba ehT dlroW'setamirP ni trapA snamuH steS eliM artxE gninnuR`

**Example2**

Original Text

`Tim Duncan Leads Spurs Past 76ers 88-80 (AP) AP - The Philadelphia 76ers got a firsthand demonstrati`

Generated Text

`itartsnomed dnahtsrif a tog sre67 aihpledalihP ehT - PA )PA( 08-88 sre67 tsaP srupS sdaeL nacnuD miT`

Actual Reverse Text

`itartsnomed dnahtsrif a tog sre67 aihpledalihP ehT - PA )PA( 08-88 sre67 tsaP srupS sdaeL nacnuD miT`

For the complete prediction results, see [predictions.csv](https://github.com/GSYfate/T5-Reverse-English/blob/main/outputs/predictions.csv)

