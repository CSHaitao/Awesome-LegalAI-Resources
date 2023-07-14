
# Awesome-LegalAI-Resources

This repository aims to collect and curate resources related to Legal AI, including datasets, websites, and other useful links. Whether you are a researcher, developer, or simply interested in the intersection of law and artificial intelligence, we hope this repository provides valuable information and references.

## About
The rapid advancements in AI technologies have significantly impacted various domains, including the legal industry. The purpose of this repository is to collect and organize resources that cover a wide range of topics related to Legal AI, including but not limited to:

- Natural Language Processing (NLP) for legal text analysis
- AI-powered legal research tools
- Automated contract analysis and generation
- Predictive analytics in legal decision-making
- Legal document classification and summarization
- Ethical considerations in Legal AI
- Legal implications of AI adoption in the legal profession

This repository serves as a centralized hub for researchers, practitioners, and enthusiasts to discover, share, and collaborate on Legal AI resources. Whether you're looking for tutorials, datasets, websites or open-source projects, you'll find valuable material here.

## General Corpus

- **MultiLegalPile**: A 689GB corpus in 24 languages from 17 jurisdictions.
    [Paper](https://arxiv.org/abs/2306.02069v2) [Link](https://huggingface.co/datasets/joelito/Multi_Legal_Pile)

    **Language**: multilingual  **Country**: multinational

- **MC4_legal**: This dataset contains large text resources (~106GB in total) from mc4 filtered for legal data that can be used for pretraining language models.
    [Link](https://huggingface.co/datasets/joelito/legal-mc4)

    **Language**: multilingual  **Country**: multinational

- **EurlexResources**: This dataset contains large text resources (~179GB in total) from EURLEX that can be used for pretraining language models.
    [Link](https://huggingface.co/datasets/joelito/eurlex_resources)

    **Language**: multilingual  **Country**: multinational

- **LeXFile**: The LeXFiles is a new diverse English multinational legal corpus that we created including 11 distinct sub-corpora that cover legislation and case law from 6 primarily English-speaking legal systems (EU, CoE, Canada, US, UK, India). The corpus contains approx. 19 billion tokens.
   [Paper](https://arxiv.org/abs/2305.07507) [Link](https://huggingface.co/datasets/lexlms/lex_files)

    **Language**: English  **Country**: multinational

- **Pile of Law**: A 256GB (and growing) dataset of open-source English-language legal and administrative data, covering court opinions, contracts, administrative rules, and legislative records.
    [Paper](https://arxiv.org/abs/2207.00220) [Link](https://github.com/Breakend/PileOfLaw)

    **Language**: English  **Country**: Unknown

- **Spanish Legal Domain Corpora**: Our corpora comprises multiple digital resources and it has a total of 8.9GB of textual data.
    [Paper](https://arxiv.org/abs/2110.12201) [Link](https://github.com/PlanTL-GOB-ES/lm-legal-es)

    **Language**: Spanish  **Country**: Spanish


## Evaluation Benchmark

### Multi Legal Task

- **LegalLAMA**: LegalLAMA is a diverse probing benchmark suite comprising 8 sub-tasks that aims to assess the acquaintance of legal knowledge that PLMs acquired in pre-training.
    [Paper](https://arxiv.org/abs/2305.07507) [Link](https://huggingface.co/datasets/lexlms/legal_lama)

    **Language**: English  **Country**: multinational

- **LexGLUE**: LexGLUE comprises seven datasets: ECtHR Task A and B, SCOTUS, EUR-LEX, LEDGAR, UNFAIR-ToS, and CaseHOLD that are available for re-use and re-share with appropriate attribution.
    [Paper](https://arxiv.org/abs/2110.00976) [Link](https://github.com/coastalcph/lex-glue)

    **Language**: English  **Country**: multinational

- **LEXTREME**: The dataset consists of 11 diverse multilingual legal NLU datasets. 6 datasets have one single configuration and 5 datasets have two or three configurations. This leads to a total of 18 tasks.
    [Paper](https://arxiv.org/abs/2301.13126) [Link](https://huggingface.co/datasets/joelito/lextreme)

    **Language**: multilingual  **Country**: multinational

- **LegalBench**: LegalBench is a collaborative benchmark intended to evaluate English large language models on legal reasoning and legal text-based tasks. LegalBench currently consists of more than 90 tasks.
    [Paper](https://arxiv.org/abs/2209.06120) [Link](https://github.com/HazyResearch/legalbench)

    **Language**: English  **Country**: multinational

- **LBOX OPEN**: This paper present the first large-scale benchmark of Korean legal AI datasets, LBOX OPEN, that consists of one legal corpus, two classification tasks, two legal judgement prediction (LJP) tasks, and one summarization task.
    [Paper](https://arxiv.org/abs/2206.05224) [Link](https://github.com/lbox-kr/lbox-open)
    
    **Language**: Korean  **Country**: Korean

### Legal Case Retrieval

- **LeCaRD**: LeCaRD composes of 107 query cases and 10,700 candidate cases selected from a corpus
of over 43,000 Chinese criminal judgements.
    [Paper](https://dl.acm.org/doi/10.1145/3404835.3463250) [Link](https://github.com/myx666/LeCaRD)

    **Language**: Chinese  **Country**: China

- **LeCaRDv2**: LeCaRDv2 is one of the largest Chinese legal case retrieval datasets with the widest coverage of criminal charges. The dataset comprises 800 query cases and 55,192 candidate cases extracted from 4.3 million criminal case documents.
    [Link](https://github.com/THUIR/LeCaRDv2)

    **Language**: Chinese  **Country**: China

- **COLIEE**: The Competition on Legal Information Extraction/Entailment (COLIEE)  is an annual international competition whose aim is to achieve state-of-the-art methods for legal text processing. Task 1 is the legal case retrieval task. Task 3 is the statute law retrieval task.
    [Paper](https://sites.ualberta.ca/~rabelo/COLIEE2023/COLIEE2022_summary.pdf) [Link](https://sites.ualberta.ca/~rabelo/COLIEE2023/)

    **Language**: English/Japanese  **Country**: Canada/Japan

- **document-similarity**: The task here is to calculate a similarity score (in the range 0-1) between two case documents. The dataset collected 53, 210 publicly available case documents from the Supreme Court of India and and 12, 814 Acts from the Indian judiciary.
    [Paper](https://arxiv.org/abs/2209.12474) [Link](https://github.com/Law-AI/document-similarity)

    **Language**: English  **Country**: India

### Question Answering

- **JEC-QA**: the largest question answering dataset in the legal domain, collected from the National Judicial Examination of China. There are 26,365 questions in JEC-QA.
    [Paper](https://arxiv.org/abs/1911.12011) [Link](https://jecqa.thunlp.org/)

    **Language**: Chinese  **Country**: China

- **CaseHOLD**: This CaseHOLD dataset provides 53,000+ multiple choice questions with prompts from a judicial decision and multiple potential holdings, one of which is correct, that could be cited.
    [Paper](https://dl.acm.org/doi/10.1145/3462757.3466088) [Link](https://github.com/reglab/casehold)
    
    **Language**: English  **Country**: America

- **SARA**: A novel dataset based on US tax law, together with test cases.
    [Paper](https://ceur-ws.org/Vol-2645/paper5.pdf) [Link](https://nlp.jhu.edu/law/)
    
    **Language**: English  **Country**: America

- **PrivacyQA**: PrivacyQA is a corpus consisting of 1750 questions about the contents of privacy policies, paired with expert annotations. 
    [Paper](https://ceur-ws.org/Vol-2645/paper5.pdf) [Link](https://github.com/AbhilashaRavichander/PrivacyQA_EMNLP)
    
    **Language**: English  **Country**: America


### Legal Case Entailment

- **COLIEE**: The Competition on Legal Information Extraction/Entailment (COLIEE)  is an annual international competition whose aim is to achieve state-of-the-art methods for legal text processing. Task 2 is the legal case entailment task. Task 4 is the legal textual entailment data corpus.
    [Paper](https://sites.ualberta.ca/~rabelo/COLIEE2023/COLIEE2022_summary.pdf) [Link](https://sites.ualberta.ca/~rabelo/COLIEE2023/)

    **Language**: English/Japanese  **Country**: Canada/Japan

- **Legal Linking**: This paper describes a dataset and baseline systems for linking paragraphs from court cases to clauses or amendments in the US Constitution.
    [Paper](https://aclanthology.org/W19-2205.pdf) [Link](https://github.com/mayhewsw/legal-linking)
    
    **Language**: English  **Country**: America

### Document classification 

- **CAIL2018**: CAIL2018 contains more than 2.6 million criminal cases published by the Supreme People’s Court of China.  It consists of applicable law articles, charges, and prison terms, which are expected to be inferred according to the fact descriptions of cases.
    [Paper](https://arxiv.org/abs/1807.02478) [Link](https://github.com/thunlp/CAIL2018)
    
    **Language**: Chinese  **Country**: China

- **ECHR**: This paper contributes a new publicly available English legal judgment prediction dataset of cases from the European Court of Human Rights (~11.5k cases).
    [Paper](https://aclanthology.org/P19-1424/) [Link](https://archive.org/details/ECHR-ACL2019)
    
    **Language**: English  **Country**: European





### Summarization 

### Entity extraction


## Websites


## Contact

If you believe there's any missing resources or have any questions, suggestions, or concerns, please feel free to open an issue on the repository or contact us via email liht22@mails.tsinghua.edu.cn.


## License
This repository is licensed under the [MIT](LICENSE) License. You are free to use, modify, and distribute the content of this repository for both commercial and non-commercial purposes. However, we kindly request that you provide attribution by linking back to this repository.

---

We hope you find the Awesome-LegalAI-Resource Repository valuable and discover new insights and tools for your Legal AI journey. If you have any questions, suggestions, or concerns, please don't hesitate to open an issue. Happy exploring!