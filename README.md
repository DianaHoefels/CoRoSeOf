## CoRoSeOf - An Annotated Corpus of Romanian Sexist and Offensive Language

CoRoSeOf is a Romanian corpus of social media content annotated for sexist and offensive language. It contains approximately **40,000 samples**, of which around **10% are labeled as sexist** and **11% as offensive**.

To the best of our knowledge, CoRoSeOf is **the first annotated corpus of sexist and offensive language for Romanian**, and **the largest annotated corpus of its kind worldwide**.

## Dataset Format

The corpus includes the following columns:

- **ID**
- **Sample**
- **Text**
- **Annotator 1**
- **Gender 1**
- **Answer 1**
- **Annotator 2**
- **Gender 2**
- **Answer 2**
- **Annotator 3**
- **Gender 3**
- **Answer 3**
- **Majority Vote**
- **Final Labels**

## Folder Structure

This repository is organized as follows:

- **corpus/**, contains tweet IDs, sampling technique, annotator IDs and gender, non-aggregated annotations, majority-vote labels, and final labels
- **docs/**, contains the annotation guidelines and the keyword lists used to collect the data

## Authors

- **Diana Constantina Höfels**  
  diana.hoefels@gmail.com

- **Dr. Çağrı Çöltekin**  
  http://coltekin.net/cagri/

- **Dr. Irina Diana Mădroane**  
  irina.madroane@e-uvt.ro

## License

The corpus is distributed under the terms of the [CC BY-SA license](https://github.com/DianaHoefels/CoRoSeOf/blob/main/LICENSE).

## Paper

This dataset was presented at **LREC 2022**:

**Hoefels, D. C., Çöltekin, Ç., & Mădroane, I. D. (2022). _CoRoSeOf. An Annotated Corpus of Romanian Sexist and Offensive Tweets_.**  
[Read the paper](http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.243.pdf)

If you use this corpus in your research, please cite:

```

@InProceedings{hoefels-ltekin-mdroane:2022:LREC,
  author    = {Hoefels, Diana Constantina,  Çöltekin, Çağrı  and  Mădroane, Irina Diana},
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
## Acknowledgements

The annotators team (in alphabetical order), Anamaria Andrei, Raluca Ardeaun, Edward Bojboi, Octavia Cojocaru, Cristiana Giurcă, Costel Olaru, Roberta Recalo, Diana Stanciu, Tiberiu Tomescu and Carmen Tuns, from [Interdisciplinary Center of Gender Studies - West University of Timișoara.](www.genderstudies.uvt.ro)

This study utilized Twitter data sets and the content provided remains subject to the terms and conditions of Twitter [Twitter's Developer Agreement & Policy](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and must agree to the [Twitter Terms of Service, Privacy Policy](https://twitter.com/en/tos), [Developer Agreement](https://developer.twitter.com/en/developer-terms/agreement), and [Developer Policy](https://developer.twitter.com/en/developer-terms/policy).
