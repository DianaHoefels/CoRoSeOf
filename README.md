# CoRoSeOf
### A Large-Scale Annotated Corpus of Romanian Sexist and Offensive Language

<p align="center">

![License](https://img.shields.io/badge/License-CC--BY--SA-blue.svg)
![LREC 2022](https://img.shields.io/badge/LREC-2022-success)
![Language](https://img.shields.io/badge/Language-Romanian-red)
![Samples](https://img.shields.io/badge/Samples-39,245-orange)

</p>

<p align="center">
<strong>LREC 2022</strong> • <strong>39,245 Manually Annotated Tweets</strong> • <strong>CC BY-SA License</strong>
</p>

---

## Overview

**CoRoSeOf** is a large-scale corpus of Romanian Twitter posts manually annotated for **sexist** and **offensive** language. Developed to support research in abusive language detection and Romanian Natural Language Processing, the corpus consists of **39,245 tweets**, each independently annotated by multiple human annotators following comprehensive annotation guidelines.

To the best of our knowledge, CoRoSeOf is:

- 🇷🇴 the **first publicly available Romanian corpus** annotated for both **sexist** and **offensive** language;
- 🌍 one of the **largest manually annotated datasets** for sexism detection worldwide;
- 🔓 released under the **CC BY-SA** license to promote open and reproducible research.

---

## Highlights

- 🇷🇴 **Language:** Romanian
- 📚 **39,245 manually annotated tweets**
- 👥 **Three independent annotators** per sample
- 🏷️ **Sexism and offensiveness annotations**
- 📄 **Published at LREC 2022**
- 🔓 **Openly available under CC BY-SA**

---

## Dataset Statistics

| Property | Value |
|-----------|------:|
| **Language** | Romanian |
| **Domain** | Twitter |
| **Total Samples** | **39,245** |
| **Sexist Samples** | ~10% |
| **Offensive Samples** | ~11% |
| **Annotation** | Three independent human annotators |
| **Final Labels** | Majority vote + expert verification |

---

## Dataset Structure

Each entry in the corpus contains the following information:

| Column | Description |
|---------|-------------|
| `ID` | Unique sample identifier |
| `Sample` | Original tweet identifier |
| `Text` | Tweet text |
| `Annotator 1–3` | Annotator identifiers |
| `Gender 1–3` | Annotator gender |
| `Answer 1–3` | Individual annotations |
| `Majority Vote` | Aggregated label |
| `Final Labels` | Final curated annotation |

---

## Repository Structure

```text
CoRoSeOf/
├── corpus/
│   ├── tweet IDs
│   ├── sampling information
│   ├── annotator metadata
│   ├── individual annotations
│   ├── majority-vote labels
│   └── final labels
│
├── docs/
│   ├── annotation guidelines
│   └── keyword lists used for data collection
│
└── LICENSE
```

---

## Publication

This corpus was introduced in:

> **Hoefels, D. C., Çöltekin, Ç., & Mădroane, I. D. (2022).**  
> **CoRoSeOf: An Annotated Corpus of Romanian Sexist and Offensive Tweets.**  
> *Proceedings of the Language Resources and Evaluation Conference (LREC 2022), Marseille, France.*

📄 **Paper**  
http://www.lrec-conf.org/proceedings/lrec2022/pdf/2022.lrec-1.243.pdf

📚 **ACL Anthology**  
https://aclanthology.org/2022.lrec-1.243/

---

## Citation

If you use **CoRoSeOf** in your research, please cite:

```bibtex
@inproceedings{hoefels-ltekin-mdroane-2022-lrec,
  author    = {Hoefels, Diana Constantina and
               Çöltekin, Çağrı and
               Mădroane, Irina Diana},
  title     = {CoRoSeOf: An Annotated Corpus of Romanian Sexist and Offensive Tweets},
  booktitle = {Proceedings of the Language Resources and Evaluation Conference},
  year      = {2022},
  month     = jun,
  address   = {Marseille, France},
  publisher = {European Language Resources Association},
  pages     = {2269--2281},
  url       = {https://aclanthology.org/2022.lrec-1.243}
}
```

---

## Research Applications

CoRoSeOf supports research in:

- Abusive Language Detection
- Offensive Language Identification
- Sexism Detection
- Hate Speech Detection
- Toxicity Classification
- Bias and Fairness in NLP
- Romanian Natural Language Processing
- Computational Social Science
- Large Language Model Evaluation
- Benchmarking Transformer and Large Language Models

---

## Authors

**Diana Constantina Höfels**  
📧 diana.hoefels@gmail.com

**Dr. Çağrı Çöltekin**  
🌐 http://coltekin.net/cagri/

**Dr. Irina Diana Mădroane**  
📧 irina.madroane@e-uvt.ro

---

## License

This dataset is distributed under the **Creative Commons Attribution-ShareAlike (CC BY-SA)** license.

For details, see the [LICENSE](LICENSE) file.

---

## Acknowledgements

We gratefully acknowledge the contribution of the annotation team from the **Interdisciplinary Center of Gender Studies, West University of Timișoara**:

Anamaria Andrei • Raluca Ardeaun • Edward Bojboi • Octavia Cojocaru • Cristiana Giurcă • Costel Olaru • Roberta Recalo • Diana Stanciu • Tiberiu Tomescu • Carmen Tuns

---

## Twitter Data Notice

This dataset contains Twitter-derived content and is distributed in accordance with Twitter's Developer Agreement and Policy.

Users of this corpus are responsible for complying with the following terms when accessing or redistributing Twitter content:

- Twitter Terms of Service
- Twitter Privacy Policy
- Twitter Developer Agreement
- Twitter Developer Policy

---

## Contributing

Bug reports, suggestions, and research collaborations are welcome. Please open an issue or submit a pull request if you identify errors or have ideas for improving the repository.

---

## Citation Reminder

If **CoRoSeOf** contributes to your research, please consider citing the accompanying **LREC 2022** publication.
