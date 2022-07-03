## CoRoSeOf: An annotated Corpus of Romanian Sexist and Offensive Language

CoRoSeOf is a manually annotated corpus of Romanian sexist and offensive language, it includes roughly 40k samples divided into 10% sexist, and 11% offensive.


This file contains tweet is, sampling technique, annotator id and gender, non-aggregated annotations, and majority vote labels. 


Cite this dataset:

```
@InProceedings{hoefels-ltekin-mdroane:2022:LREC,
  author    = {Hoefels, Diana Constantina  and  Ã‡Ã¶ltekin, Ã‡aÄŸrÄ±  and  MÄƒdroane, Irina Diana},
  title     = {CoRoSeOf - An Annotated Corpus of Romanian Sexist and Offensive Tweets},
  booktitle      = {Proceedings of the Language Resources and Evaluation Conference},
  month          = {June},
  year           = {2022},
  address        = {Marseille, France},
  publisher      = {European Language Resources Association},
  pages     = {2269--2281},
  abstract  = {This paper introduces CoRoSeOf, a large corpus of Romanian social media manually annotated for sexist and offensive language. We describe the annotation process of the corpus, provide initial analyses, and baseline classification results for sexism detection on this data set. The resulting corpus contains 39 245 tweets, annotated by multiple annotators (with an agreement rate of Fleissâ€™Îº= 0.45), following the sexist label set of a recent study. The automatic sexism detection yields scores similar to some of the earlier studies (macro averaged F1 score of 83.07\% on binary classification task). We release the corpus with a permissive license.},
  url       = {https://aclanthology.org/2022.lrec-1.243}
}
```
## Folder Structure

This project is organized into the following folders:
- corpus (it contains .tsv file)
- docs (annotation guidelines and keywords used to query the data)
- scripts (corpus data processing scripts)

## Authors

Contributors names and contact info:

[Diana Constantina Höfels](diana-constantina.hoefels@student.uni-tuebingen.de)
[Çağrı Çöltekin](http://coltekin.net/cagri/)
[Irina Diana Mădroane](irina.madroane@e-uvt.ro)

## Acknowledgements

The annotators team (in alphabetical order), Anamaria Andrei, Raluca Ardeaun, Edward Bojboi, Octavia Cojocaru, Cristiana Giurcă, Costel Olaru, Roberta Recalo, Diana Stanciu, Tiberiu Tomescu and Carmen Tuns, from [Interdisciplinary Center of Gender Studies - West University of Timișoara.](www.genderstudies.uvt.ro)

This study utilized Twitter data sets and the content provided remains subject to the terms and conditions of Twitter [Twitter's Developer Agreement & Policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and must agree to the [Twitter Terms of Service, Privacy Policy](https://twitter.com/en/tos), [Developer Agreement](https://developer.twitter.com/en/developer-terms/agreement), and [Developer Policy](https://developer.twitter.com/en/developer-terms/policy).
The corpus can be used under the terms of [CC-BY-SA](https://github.com/DianaHoefels/CoRoSeOf/blob/main/LICENSE).
