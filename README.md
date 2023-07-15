
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

- **GeLeCo**: GeLeCo is a large German Legal Corpus for research, teaching and translation purposes. It includes the complete collection of federal laws, administrative regulations and court decisions published on three online databases by the German Federal Ministry of Justice and Consumer Protection and the Federal Office of Justice.
    [Link](https://github.com/antcont/GeLeCo)

    **Language**: German  **Country**: German

- **CourtListener**: The original Court Listener dataset is a collection of every court opinion published by every court in the United States. It covers 406 jurisdictions (out of 423), with opinions from the year 1754 up to now. It is constantly updated with newly filed opinions, and digitized archives.
    [Link](https://www.courtlistener.com/help/api/bulk-data/)

    **Language**: English  **Country**: America

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

- **GENTLE**: We present GENTLE, a new mixed-genre English challenge corpus totaling 17K tokens and consisting of 8 unusual text types for out-of domain evaluation: dictionary entries, esports commentaries, legal documents, medical notes, poetry, mathematical proofs, syllabuses, and threat letters. 
    [Paper](https://arxiv.org/abs/2306.01966) [Link](https://github.com/gucorpling/gentle)
    
    **Language**: English  **Country**: Unknown

- **SCALE**: In this paper, we introduce a novel NLP benchmark that poses challenges to current LLMs across four key dimensions: processing long documents (up to 50K tokens), utilizing domain specific knowledge (embodied in legal texts), multilingual understanding (covering five languages), and multitasking (comprising legal document to document Information Retrieval, Court View Generation, Leading Decision Summarization, Citation Extraction, and eight challenging Text Classification tasks).
    [Paper](https://arxiv.org/abs/2306.09237) [Link](https://huggingface.co/rcds)
    
    **Language**: multilingual  **Country**: Switzerland

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
    [Paper](https://arxiv.org/abs/1911.00841) [Link](https://github.com/AbhilashaRavichander/PrivacyQA_EMNLP)
    
    **Language**: English  **Country**: America


### Legal Case Entailment

- **COLIEE**: The Competition on Legal Information Extraction/Entailment (COLIEE)  is an annual international competition whose aim is to achieve state-of-the-art methods for legal text processing. Task 2 is the legal case entailment task. Task 4 is the legal textual entailment data corpus.
    [Paper](https://sites.ualberta.ca/~rabelo/COLIEE2023/COLIEE2022_summary.pdf) [Link](https://sites.ualberta.ca/~rabelo/COLIEE2023/)

    **Language**: English/Japanese  **Country**: Canada/Japan

- **Legal Linking**: This paper describes a dataset and baseline systems for linking paragraphs from court cases to clauses or amendments in the US Constitution.
    [Paper](https://aclanthology.org/W19-2205.pdf) [Link](https://github.com/mayhewsw/legal-linking)
    
    **Language**: English  **Country**: America

### Document Classification 

- **CAIL2018**: CAIL2018 contains more than 2.6 million criminal cases published by the Supreme People’s Court of China.  It consists of applicable law articles, charges, and prison terms, which are expected to be inferred according to the fact descriptions of cases.
    [Paper](https://arxiv.org/abs/1807.02478) [Link](https://github.com/thunlp/CAIL2018)
    
    **Language**: Chinese  **Country**: China

- **ECHR**: This paper contributes a new publicly available English legal judgment prediction dataset of cases from the European Court of Human Rights (~11.5k cases).
    [Paper](https://aclanthology.org/P19-1424/) [Link](https://archive.org/details/ECHR-ACL2019)
    
    **Language**: English  **Country**: European

- **Swiss-Judgment-Prediction**: The paper publicly release a multilingual (German, French, and Italian), diachronic (2000-2020) corpus of 85K cases from the Federal Supreme Court of Switzer- land (FSCS).
    [Paper](https://aclanthology.org/2021.nllp-1.3/) [Link](https://github.com/joelniklaus/swissjudgementprediction)

    **Language**: multilingual  **Country**: multinational

- **German Legal Decision Corpora**:To meet this need for publicly available German legal text corpora this paper presents two German legal text corpora. The first corpus contains 32,748 decisions from 131 German courts, enriched with metadata. The second one is a subset of the first corpus and consists of 200 randomly chosen judgements.
    [Paper](https://www.scitepress.org/PublishedPapers/2021/101873/101873.pdf) [Link](https://zenodo.org/record/3936490#.X1ed7ovgomK)

    **Language**: German  **Country**: German

- **EURLEX57K**:We release a new dataset of 57k legislative documents from EUR-LEX, the European Union’s public document database, annotated with concepts from EUROVOC, a multidisciplinary thesaurus.
    [Paper](https://aclanthology.org/W19-2209/) [Link](http://nlp.cs.aueb.gr/software_and_datasets/EURLEX57K/)

    **Language**: English  **Country**: European

- **German rental agreements**:601 sentences from the tenancy law of the German Civil Code and 312 sentences, classified according to a semantic type system consisting of 9 different classes, from German rental agreements.
    [Paper](https://www.researchgate.net/publication/332171940_Classifying_Semantic_Types_of_Legal_Sentences_Portability_of_Machine_Learning_Models) [Link](https://github.com/sebischair/Legal-Sentence-Classification-Datasets-and-Models)

    **Language**: English  **Country**: German


### Summarization 

- **BillSum**: We introduce the BillSum dataset, which contains a primary corpus of 22,218 US Congressional bills and reference summaries split into a train and a test set.
    [Paper](https://aclanthology.org/D19-5406/) [Link](https://huggingface.co/datasets/billsum)

    **Language**: English  **Country**: America

- **EUR-Lex-Sum**: We obtain up to 1,500 document/summary pairs per language, including a subset of 375 crosslingually aligned legal acts with texts available in all 24 languages.
    [Paper](https://arxiv.org/abs/2210.13448) [Link](https://huggingface.co/datasets/dennlinger/eur-lex-sum)

    **Language**: multilingual  **Country**: European

- **Plain English Summarization of Contracts**: The dataset we propose contains 446 sets of parallel text.
    [Paper](https://www.aclweb.org/anthology/W19-2201) [Link](https://github.com/lauramanor/legal_summarization#plain-english-summarization-of-contracts)

    **Language**: English  **Country**: America

- **Summarization-of-Privacy-Policies**: This dataset was extracted from the text of privacy policy, terms of service, and cookie policy of 151 companies. The Points and Plain English Summaries are extracted from tosdr.org.
    [Paper](https://ceur-ws.org/Vol-2645/paper3.pdf) [Link](https://github.com/senjed/Summarization-of-Privacy-Policies)

    **Language**: English  **Country**: Unknown

- **Multi-LexSum**: We introduce Multi-LexSum, a collection of 9,280 expert-authored summaries drawn from ongoing CRLC writing.
    [Paper](https://arxiv.org/abs/2206.10883) [Link](https://multilexsum.github.io/)

    **Language**: English  **Country**: Unknown



### Entity extraction
 
- **CDJUR-BR**: We describe the development of the Golden Collection of the Brazilian Judiciary (CDJUR-BR) contemplating a set of fine-grained named entities that have been annotated by experts in legal documents. This contains 44,526 annotations for 21 entities.
    [Paper](https://arxiv.org/abs/2305.18315) [Link](https://huggingface.co/datasets/dennlinger/eur-lex-sum)

    **Language**: Portuguese  **Country**: Brazilian

- **Extracting Contract Elements**: The paper describes and is accompanied by a new benchmark dataset of approximately 3,500 English contracts with gold contract element annotations.
    [Paper](http://nlp.cs.aueb.gr/pubs/icail2017.pdf)

    **Language**: English  **Country**: England

- **LEVEN**: LEVEN contains 108 event types in total, including 64 charge-oriented events and 44 general events. Their distribution is shown below.
    [Paper](https://aclanthology.org/2022.findings-acl.17.pdf) [Link](https://github.com/thunlp/LEVEN)

    **Language**: Chinese  **Country**: China

### Others

- **MAUD**: To address this challenge, we introduce the Merger Agreement Understanding Dataset (MAUD), an expert-annotated reading comprehension dataset based on the American Bar Association’s 2021 Public Target Deal Points Study, with over 39,000 examples and over 47,000 total annotations.
    [Paper](https://arxiv.org/abs/2301.00876) [Link](https://drive.google.com/drive/folders/1RujOK2FZKdFSCJ15tqdyd42g8WLsYagj)

    **Language**: English  **Country**: America

- **VerbCL**: This paper presents a new dataset that consists of the citation graph of court opinions, which cite previously published court opinions in support of their arguments.
    [Paper](https://arxiv.org/abs/2108.10120) [Link](https://uvaauas.figshare.com/articles/dataset/VerbCL_Dataset/14798878/1)

    **Language**: English  **Country**: America

- **MultiLegalSBD**: Sentence Boundary Detection (SBD) is one of the foundational building blocks of Natural Language Processing (NLP), with incorrectly split sentences heavily influencing the output quality of downstream tasks. We curated a diverse multilingual legal dataset consisting of over 130'000 annotated sentences in 6 languages.
    [Paper](https://arxiv.org/abs/2305.01211) [Link](https://huggingface.co/datasets/rcds/MultiLegalSBD)

    **Language**: multilingual  **Country**: multinational

- **FairLex**: Our benchmarks cover four jurisdictions (European Council, USA, Switzerland, and China), five languages (English, German, French, Italian and Chinese) and fairness across five attributes (gender, age, region, language, and legal area).
    [Paper](https://arxiv.org/abs/2203.07228) [Link](https://huggingface.co/datasets/coastalcph/fairlex)

    **Language**: multilingual  **Country**: multinational

- **ContractNLI**: In this work, we propose documentlevel natural language inference (NLI) for contracts, a novel, real-world application of NLI that addresses such problems. We annotated and release the largest corpus to date consisting of 607 annotated contracts.
    [Paper](https://arxiv.org/abs/2110.01799) [Link](https://stanfordnlp.github.io/contract-nli/)

    **Language**: English  **Country**: America

- **Demosthen**: A novel corpus for argument mining in legal documents, composed of 40 decisions of the Court of Justice of the European Union on matters of fiscal state ai.
    [Paper](https://aclanthology.org/2022.argmining-1.14.pdf) [Link](https://github.com/adele-project/demosthenes)

    **Language**: English  **Country**: European

## Websites
- https://flk.npc.gov.cn/ all Chinese laws and regulations.

- https://wenshu.court.gov.cn/ judicial documents in China.

- https://www.westlaw.com/: a well-known legal research platform that provides access to legal documents, cases, statutes, commentaries, and legal news from around the world.

- https://www.lexisnexis.com/: another widely used legal research tool that offers global legal documents, cases, statutes, news, and commentaries.

- https://home.heinonline.org/: a specialized legal and law-related research database that includes legal documents, journals, statutes, and more from the United States and other countries.

- https://case.law/ all official, book-published United States case law.

- https://www.legifrance.gouv.fr/ a French legal publisher providing access to law codes and legal decisions.

- http://scdb.wustl.edu/ information about every case decided by the US Supreme Court between 1791 and today.

- https://www.statmt.org/europarl/ Parallel text of the proceedings of the European Parliment, collected in 11 languages.

- https://uscode.house.gov/download/download.shtml downloadable version of the US Code in XML format

- https://www.uspto.gov/ip-policy/economic-research/research-datasets/patent-litigation-docket-reports-data detailed patent litigation data on over 80k unique district court cases

- https://curia.europa.eu/jcms/jcms/j_6/: the official website of the European Court of Justice, offering access to European Union legal documents and cases.

- https://www.justia.com/: provides access to a wide range of legal information, including cases, statutes, regulations, and legal articles. Covers both U.S. federal and state laws.

- https://www.findlaw.com/: offers legal resources and information, including cases, statutes, regulations, and legal news. Covers U.S. federal and state laws.

- https://www.courtlistener.com/: a free legal research platform that provides access to U.S. federal and state court cases, along with other legal documents and opinions.

- https://www.pacer.gov/: the Public Access to Court Electronic Records (PACER) system provides access to U.S. federal court documents, including case filings, docket information, and court opinions. Registration and fees may apply.

- https://www.law.cornell.edu/: operated by Cornell Law School, the LII offers access to U.S. federal and state laws, regulations, and court cases, along with legal articles and resources.

- https://www.bailii.org/: provides access to legal materials from the United Kingdom and Ireland, including cases, legislation, and legal journals.

- https://www.austlii.edu.au/: Offers access to legal materials from Australia and neighboring countries, including cases, legislation, treaties, and law reform reports.

- https://www.canlii.org/: Provides access to Canadian legal documents, including cases, statutes, regulations, and court rules.

- http://www.worldlii.org/: a free and independent global legal research resource, aggregating legal materials from various countries and regions.


## Contact

If you believe there's any missing resources or have any questions, suggestions, or concerns, please feel free to open an issue on the repository or contact us via email liht22@mails.tsinghua.edu.cn.


## License
This repository is licensed under the [MIT](LICENSE) License. You are free to use, modify, and distribute the content of this repository for both commercial and non-commercial purposes. However, we kindly request that you provide attribution by linking back to this repository.

---

We hope you find the Awesome-LegalAI-Resource Repository valuable and discover new insights and tools for your Legal AI journey. If you have any questions, suggestions, or concerns, please don't hesitate to open an issue. Happy exploring!