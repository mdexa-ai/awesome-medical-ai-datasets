# Awesome Medical AI Datasets

Medical AI datasets and open models, grouped by domain. Each row gives the license verdict, the main conditions, the source risk flags and how the data is obtained, and links to a dated record with the quoted source text in the [Mdexa database](https://mdexa.com). The list is generated from those records and regenerated at each data release; current coverage is at https://mdexa.com/v1/stats.

Other languages: [中文](README.zh.md)

## Contents

- [Clinical medicine](#clinical-medicine)
- [Pharmacy and drugs](#pharmacy-and-drugs)
- [Genomics and omics](#genomics-and-omics)
- [Biomedical literature](#biomedical-literature)
- [Traditional Chinese medicine](#traditional-chinese-medicine)
- [Standards and terminology](#standards-and-terminology)
- [Drug lists and formularies](#drug-lists-and-formularies)
- [Open models](#open-models)
- [How to read this list](#how-to-read-this-list)
- [About this list](#about-this-list)

## Clinical medicine

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [BianQueCorpus（扁鹊健康大数据）](https://mdexa.com/datasets/bianque-corpus/) | `restricted` | LicenseRef-THUDM-ChatGLM-6B-Model-License; commercial use: no; derivatives: unverified; redistribution: unverified | derived, scraped, real-patient-text | Link only | 2026-11-12 |
| [CBLUE](https://mdexa.com/datasets/cblue/) | `unstated` (repo license only) | n/a (no license conclusion) | none | Link only | 2026-11-12 |
| [ChatMed_Consult_Dataset](https://mdexa.com/datasets/chatmed-consult-dataset/) | `conflict` (unsigned) | unsigned: see the card | scraped, model-generated | Public | 2026-11-12 |
| [Chinese-medical-dialogue-data（Toyhom）](https://mdexa.com/datasets/chinese-medical-dialogue-data/) | `permissive` (flagged) | MIT | unknown-provenance | Link only | 2026-11-12 |
| [ClinicalTrials.gov](https://mdexa.com/datasets/clinicaltrials-gov/) | `unstated` | n/a (no license conclusion) | none | Public | 2026-11-13 |
| [ClinPGx/PharmGKB](https://mdexa.com/datasets/pharmgkb/) | `restricted` | LicenseRef-Stanford-University-terms; commercial use: no; derivatives: conditional; redistribution: conditional; attribution; share-alike; keep notices | none | Link only | 2026-11-13 |
| [CMB (Chinese Medical Benchmark)](https://mdexa.com/datasets/cmb/) | `permissive` (flagged) | Apache-2.0 | exam-derived | Public | 2026-11-12 |
| [cMedQA2](https://mdexa.com/datasets/cmedqa2/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | none | Link only | 2026-11-12 |
| [CMExam](https://mdexa.com/datasets/cmexam/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | exam-derived | Public | 2026-11-12 |
| [CMKG（中文多模态医学知识图谱）](https://mdexa.com/datasets/cmkg/) | `unstated` | n/a (no license conclusion) | scraped | Link only | 2026-11-12 |
| [CMtMedQA](https://mdexa.com/datasets/cmtmedqa/) | `permissive` (flagged) | MIT | real-patient-text | Public | 2026-11-12 |
| [DiagnosisArena](https://mdexa.com/datasets/diagnosisarena/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | real-patient-text | Public | 2026-11-14 |
| [DiaKG（糖尿病知识图谱标注数据）](https://mdexa.com/datasets/diakg/) | `unverifiable` | n/a (no license conclusion) | none | Link only | 2026-11-12 |
| [DISC-Med-SFT](https://mdexa.com/datasets/disc-med-sft/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | derived, scraped, real-patient-text, model-generated | Public | 2026-11-12 |
| [EgoExOR: An Egocentric–Exocentric Operating Room Dataset for Comprehensive Understanding of Surgical Activities](https://mdexa.com/datasets/egoexor/) | `permissive` | Apache-2.0; keep notices | none | Public | 2026-11-14 |
| [ESL-bench (Event-driven Synthetic Longitudinal Benchmark)](https://mdexa.com/datasets/esl-bench/) | `conflict` (unsigned) | unsigned: see the card | none | Link only | 2026-11-14 |
| [GBaker/MedQA-USMLE-4-options-hf](https://mdexa.com/datasets/medqa-usmle-4-options-hf/) | `permissive` (flagged) | CC-BY-SA-4.0; attribution; share-alike | exam-derived | Public | 2026-11-14 |
| [HealthBench](https://mdexa.com/datasets/healthbench/) | `permissive` | MIT; keep notices | none | Public | 2026-11-14 |
| [huatuo_encyclopedia_qa](https://mdexa.com/datasets/huatuo-encyclopedia-qa/) | `permissive` (flagged) | Apache-2.0 | scraped | Public | 2026-11-12 |
| [Huatuo_knowledge_graph_qa](https://mdexa.com/datasets/huatuo-knowledge-graph-qa/) | `permissive` (flagged) | Apache-2.0; keep notices | derived | Public | 2026-11-14 |
| [Huatuo-26M](https://mdexa.com/datasets/huatuo-26m/) | `permissive` (flagged) | Apache-2.0 | scraped, real-patient-text | Link only | 2026-11-12 |
| [Huatuo-Llama-Med-Chinese 知识库问答与文献数据](https://mdexa.com/datasets/huatuo-llama-med-chinese-data/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | model-generated | Link only | 2026-11-12 |
| [Huatuo26M-Lite](https://mdexa.com/datasets/huatuo26m-lite/) | `permissive` (flagged) | Apache-2.0 | scraped, model-generated, derived | Public | 2026-11-12 |
| [huatuo26M-testdatasets](https://mdexa.com/datasets/huatuo26m-testdatasets/) | `permissive` (flagged) | Apache-2.0; keep notices | derived, real-patient-text | Public | 2026-11-14 |
| [HuatuoGPT-sft-data-v1](https://mdexa.com/datasets/huatuogpt-sft-data-v1/) | `permissive` (flagged) | Apache-2.0 | unknown-provenance | Public | 2026-11-12 |
| [HuatuoGPT2-Pretraining-Instruction](https://mdexa.com/datasets/huatuogpt2-pretraining-instruction/) | `permissive` (flagged) | Apache-2.0; keep notices | model-generated | Public | 2026-11-14 |
| [HuatuoGPT2-SFT-GPT4-140K](https://mdexa.com/datasets/huatuogpt2-sft-gpt4-140k/) | `permissive` (flagged) | Apache-2.0; keep notices | derived, model-generated | Public | 2026-11-14 |
| [IMCS-21](https://mdexa.com/datasets/imcs-21/) | `unstated` | n/a (no license conclusion) | real-patient-text | Link only | 2026-11-12 |
| [INCLUDE](https://mdexa.com/datasets/include-base-44/) | `permissive` (flagged) | Apache-2.0; keep notices | exam-derived | Public | 2026-11-14 |
| [International Clinical Trials Registry Platform (ICTRP)](https://mdexa.com/datasets/who-ictrp/) | `restricted` | LicenseRef-WHO-terms; commercial use: conditional; derivatives: conditional; redistribution: conditional; attribution | none | Link only | 2026-11-14 |
| [MedBench（上海人工智能实验室）](https://mdexa.com/datasets/medbench/) | `unverifiable` | n/a (no license conclusion) | none | Link only | 2026-11-12 |
| [MedDG](https://mdexa.com/datasets/meddg/) | `unstated` (repo license only) | n/a (no license conclusion) | scraped, real-patient-text | Link only | 2026-11-12 |
| [MedDialog-CN](https://mdexa.com/datasets/meddialog-cn/) | `unverifiable` | n/a (no license conclusion) | scraped, real-patient-text | Link only | 2026-11-12 |
| [medical-o1-reasoning-SFT（中文子集）](https://mdexa.com/datasets/medical-o1-reasoning-sft/) | `permissive` (flagged) | Apache-2.0 | model-generated | Public | 2026-11-12 |
| [Medical-Reasoning-SFT-Mega](https://mdexa.com/datasets/medical-reasoning-sft-mega/) | `permissive` (flagged) | Apache-2.0; keep notices | model-generated | Public | 2026-11-14 |
| [MedMCQA](https://mdexa.com/datasets/medmcqa/) | `permissive` (flagged) | Apache-2.0; keep notices | exam-derived, scraped | Public | 2026-11-14 |
| [medmcqa-es](https://mdexa.com/datasets/medmcqa-es/) | `permissive` (flagged) | CC-BY-4.0; attribution | derived | Public | 2026-11-14 |
| [MedQA (USMLE 4-option, US subset + English textbook corpus)](https://mdexa.com/datasets/medqa-2/) | `permissive` (flagged) | MIT; keep notices | derived, exam-derived | Public | 2026-11-14 |
| [MedQA-USMLE-4-options](https://mdexa.com/datasets/medqa-usmle-4-options/) | `permissive` (flagged) | CC-BY-4.0; attribution | exam-derived | Public | 2026-11-14 |
| [MedQA（含大陆中文题，MCMLE）](https://mdexa.com/datasets/medqa/) | `unstated` (repo license only) | n/a (no license conclusion) | exam-derived | Link only | 2026-11-12 |
| [MLEC-QA](https://mdexa.com/datasets/mlec-qa/) | `unstated` (repo license only) | n/a (no license conclusion) | exam-derived | Link only | 2026-11-12 |
| [PMC-Patients-ReCDS](https://mdexa.com/datasets/pmc-patients-recds/) | `restricted` | CC-BY-NC-SA-4.0; commercial use: no; derivatives: unstated; redistribution: unstated; attribution; share-alike | derived, real-patient-text | Public | 2026-11-14 |
| [PromptCBLUE](https://mdexa.com/datasets/promptcblue/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | derived | Link only | 2026-11-12 |
| [QASystemOnMedicalKG（医疗知识图谱）](https://mdexa.com/datasets/qasystem-medical-kg/) | `restricted` | commercial use: no; derivatives: unstated; redistribution: unstated | scraped | Link only | 2026-11-12 |
| [R2MED Benchmark](https://mdexa.com/datasets/medqa-diag/) | `unstated` (unsigned; published `permissive`) | unsigned: see the card | derived, exam-derived | Public | 2026-11-14 |
| [医学考试题库 JSON 数据集](https://mdexa.com/datasets/medical-exam-question-bank-json/) | `permissive` (flagged) | Apache-2.0; keep notices | exam-derived | Link only | 2026-11-14 |

## Pharmacy and drugs

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [ATC/DDD Index](https://mdexa.com/datasets/atc-ddd/) | `restricted` | LicenseRef-WHO-Collaborating-Centre-for-Drug-Statistics-Methodology-terms; commercial use: no; derivatives: no; redistribution: conditional; attribution; no derivatives | none | Link only | 2026-11-14 |
| [BindingDB](https://mdexa.com/datasets/bindingdb/) | `permissive` (flagged) | CC-BY-3.0; attribution; share-alike | derived | Link only | 2026-11-14 |
| [ChEMBL](https://mdexa.com/datasets/chembl/) | `permissive` | CC-BY-SA-3.0; attribution; share-alike | none | Link only | 2026-11-14 |
| [DDInter](https://mdexa.com/datasets/ddinter/) | `restricted` | LicenseRef-all-rights-reserved; commercial use: unstated; derivatives: unstated; redistribution: unstated | none | Link only | 2026-11-14 |
| [DrugBank](https://mdexa.com/datasets/drugbank/) | `restricted` | LicenseRef-OMx-Personal-Health-Analytics-DrugBank-terms; commercial use: no; derivatives: unstated; redistribution: unstated; registration required | none | Registration required | 2026-11-13 |
| [DrugCentral](https://mdexa.com/datasets/drugcentral/) | `unstated` | n/a (no license conclusion) | real-patient-text | Link only | 2026-11-14 |
| [jablonkagroup/chempile-lift](https://mdexa.com/datasets/chempile-lift/) | `restricted` | CC-BY-NC-SA-4.0; commercial use: no; derivatives: unstated; redistribution: unstated; attribution; share-alike | none | Link only | 2026-11-14 |
| [openFDA](https://mdexa.com/datasets/openfda/) | `restricted` | LicenseRef-U-S-Food-and-Drug-Administration-terms; commercial use: conditional; derivatives: conditional; redistribution: conditional; attribution | none | Link only | 2026-11-13 |
| [PubChem](https://mdexa.com/datasets/pubchem/) | `permissive` (unsigned) | unsigned: see the card | none | Link only | 2026-11-14 |
| [RxNorm](https://mdexa.com/datasets/rxnorm/) | `restricted` | LicenseRef-National-Library-of-Medicine-terms; commercial use: conditional; derivatives: unstated; redistribution: conditional; keep current | derived | Link only | 2026-11-13 |
| [THEMol: Torsion, Hessian, Energy of Molecules](https://mdexa.com/datasets/themol/) | `restricted` | CC-BY-NC-4.0; commercial use: no; derivatives: unstated; redistribution: unstated; attribution | none | Public | 2026-11-14 |
| [Therapeutics Data Commons](https://mdexa.com/datasets/tdc/) | `unstated` (repo license only) | n/a (no license conclusion) | none | Link only | 2026-11-14 |
| [TopU-LBVS: Multi-Target Benchmark for Ligand-Based Virtual Screening](https://mdexa.com/datasets/topu-lbvs/) | `permissive` (flagged) | CC-BY-SA-4.0; attribution; share-alike; keep notices | derived | Link only | 2026-11-14 |

## Genomics and omics

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [AlphaFold Protein Structure Database](https://mdexa.com/datasets/alphafold-db/) | `permissive` (flagged) | CC-BY-4.0; attribution | derived, model-generated | Link only | 2026-11-14 |
| [GEO](https://mdexa.com/datasets/geo/) | `unstated` | n/a (no license conclusion) | none | Public | 2026-11-14 |
| [gnomAD](https://mdexa.com/datasets/gnomad/) | `restricted` (unsigned; published `permissive`) | unsigned: see the card | none | Public | 2026-11-13 |
| [GTEx](https://mdexa.com/datasets/gtex/) | `unstated` | n/a (no license conclusion) | real-patient-text | Link only | 2026-11-14 |
| [KEGG: Kyoto Encyclopedia of Genes and Genomes](https://mdexa.com/datasets/kegg/) | `restricted` | LicenseRef-Kanehisa-Laboratories-terms; commercial use: conditional; derivatives: unstated; redistribution: conditional | none | Registration required | 2026-11-14 |
| [RCSB Protein Data Bank](https://mdexa.com/datasets/rcsb-pdb/) | `permissive` | CC0-1.0; attribution; keep notices | none | Link only | 2026-11-14 |
| [Reactome](https://mdexa.com/datasets/reactome/) | `permissive` (unsigned) | unsigned: see the card | none | Link only | 2026-11-14 |
| [STRING](https://mdexa.com/datasets/string/) | `permissive` (unsigned) | unsigned: see the card | none | Link only | 2026-11-14 |
| [UniProt](https://mdexa.com/datasets/uniprot/) | `permissive` | CC-BY-4.0; attribution | none | Link only | 2026-11-13 |

## Biomedical literature

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [PubMed](https://mdexa.com/datasets/pubmed-medline/) | `unstated` | n/a (no license conclusion) | derived | Link only | 2026-11-13 |
| [PubMedCausal](https://mdexa.com/datasets/pubmedcausal/) | `unstated` (unsigned; published `permissive`) | unsigned: see the card | derived | Public | 2026-11-14 |
| [PubMedQA](https://mdexa.com/datasets/pubmedqa/) | `unstated` (unsigned; published `permissive`) | unsigned: see the card | derived | Public | 2026-11-14 |

## Traditional Chinese medicine

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [Chinese Herbal Medicine Sentiment Analysis Dataset](https://mdexa.com/datasets/chinese-herbal-medicine-sentiment/) | `permissive` (flagged) | MIT; attribution; keep notices | scraped | Public | 2026-11-14 |
| [Collection of 791 Traditional Chinese Medicine books（Figshare）](https://mdexa.com/datasets/figshare-tcm-791-books/) | `unverifiable` | n/a (no license conclusion) | derived | Link only | 2026-11-12 |
| [HERB（中药高通量实验与文献数据库）](https://mdexa.com/datasets/herb/) | `unverifiable` | n/a (no license conclusion) | none | Link only | 2026-11-12 |
| [HWTCM（Haiwei 中医评测集）](https://mdexa.com/datasets/hwtcm/) | `permissive` (flagged) | MIT | unknown-provenance | Public | 2026-11-12 |
| [LingLanMedBench Traditional Chinese Medicine Benchmark Dataset](https://mdexa.com/datasets/linglan/) | `permissive` (flagged) | CC-BY-4.0; attribution; keep notices | exam-derived | Public | 2026-11-14 |
| [MedChatZH](https://mdexa.com/datasets/medchatzh/) | `conflict` (unsigned) | unsigned: see the card | none | Public | 2026-11-14 |
| [ShenNong_TCM_Dataset（ChatMed_TCM_Dataset）](https://mdexa.com/datasets/shennong-tcm-dataset/) | `conflict` (unsigned) | unsigned: see the card | model-generated | Public | 2026-11-12 |
| [TCM-3CEval](https://mdexa.com/datasets/tcm-3ceval/) | `unverifiable` | n/a (no license conclusion) | exam-derived | Link only | 2026-11-12 |
| [tcm-acupuncture-classics（中医针灸经络古籍整理）](https://mdexa.com/datasets/tcm-acupuncture-classics/) | `restricted` | LicenseRef-wangekxy-commercial; commercial use: conditional; derivatives: unverified; redistribution: no | none | Public | 2026-11-12 |
| [TCM-Ladder](https://mdexa.com/datasets/tcm-ladder/) | `permissive` (flagged) | CC-BY-4.0 | exam-derived, scraped | Public | 2026-11-12 |
| [TCM-NER（中医药说明书实体识别）](https://mdexa.com/datasets/tcm-ner/) | `unverifiable` | n/a (no license conclusion) | none | Link only | 2026-11-12 |
| [TCM-SD（辨证分型数据集）](https://mdexa.com/datasets/tcm-sd/) | `unverifiable` | n/a (no license conclusion) | real-patient-text | Link only | 2026-11-12 |
| [TCM-Text-Exams（ShizhenGPT 文本评测）](https://mdexa.com/datasets/tcm-text-exams/) | `permissive` (flagged) | Apache-2.0 | exam-derived | Public | 2026-11-12 |
| [TCM-Vision-Benchmark](https://mdexa.com/datasets/tcm-vision-benchmark/) | `permissive` (flagged) | Apache-2.0 | unknown-provenance | Public | 2026-11-12 |
| [TCMBench（TCM-ED）](https://mdexa.com/datasets/tcmbench/) | `unstated` | n/a (no license conclusion) | exam-derived | Link only | 2026-11-12 |
| [TCMEval-SDT（辨证思维评测）](https://mdexa.com/datasets/tcmeval-sdt/) | `unverifiable` | n/a (no license conclusion) | real-patient-text | Link only | 2026-11-12 |
| [TCMQA（TechTCM）](https://mdexa.com/datasets/tcmqa/) | `restricted` | CC-BY-NC-SA-4.0; commercial use: no; derivatives: conditional; redistribution: conditional | exam-derived | Public | 2026-11-12 |
| [tmmlu++](https://mdexa.com/datasets/tmmluplus/) | `permissive` (flagged) | MIT; keep notices | unknown-provenance | Public | 2026-11-14 |
| [Traditional Chinese Medicine Examination](https://mdexa.com/datasets/tcmle/) | `permissive` (flagged) | Apache-2.0; keep notices | exam-derived | Public | 2026-11-14 |
| [Traditional-Chinese-Medicine-Dataset-Pretrain](https://mdexa.com/datasets/traditional-chinese-medicine-dataset-pretrain/) | `permissive` (flagged) | Apache-2.0; keep notices | real-patient-text, scraped | Public | 2026-11-14 |
| [中医药多维知识图谱（TCM-MKG）](https://mdexa.com/datasets/tcm-mkg/) | `restricted` | CC-BY-NC-4.0; commercial use: no; derivatives: conditional; redistribution: conditional | derived | Public | 2026-11-12 |
| [殆知阁古代文献 txt 大全集（含医藏）](https://mdexa.com/datasets/daizhige-classics/) | `unstated` | n/a (no license conclusion) | none | Link only | 2026-11-12 |

## Standards and terminology

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [Human Phenotype Ontology](https://mdexa.com/datasets/hpo/) | `restricted` | LicenseRef-Human-Phenotype-Ontology-Consortium-terms; commercial use: unstated; derivatives: no; redistribution: unstated; no derivatives; keep notices; state modifications | none | Link only | 2026-11-13 |
| [ICD-11](https://mdexa.com/datasets/icd-11/) | `restricted` | CC-BY-ND-3.0-IGO; commercial use: unstated; derivatives: no; redistribution: unstated; attribution; no derivatives | none | Link only | 2026-11-14 |
| [LOINC](https://mdexa.com/datasets/loinc/) | `restricted` | LicenseRef-Regenstrief-Institute-Inc-terms; commercial use: conditional; derivatives: conditional; redistribution: conditional; keep notices | none | Link only | 2026-11-14 |
| [MedDRA](https://mdexa.com/datasets/meddra/) | `restricted` | LicenseRef-MSSO-terms; commercial use: conditional; derivatives: unstated; redistribution: unstated | none | Registration required | 2026-11-13 |
| [SNOMED CT](https://mdexa.com/datasets/snomed-ct/) | `restricted` | LicenseRef-SNOMED-International-terms; commercial use: conditional; derivatives: unstated; redistribution: conditional; depends on territory; registration required | none | Registration required | 2026-11-14 |
| [UMLS Metathesaurus](https://mdexa.com/datasets/umls/) | `restricted` | LicenseRef-National-Library-of-Medicine-terms; commercial use: unstated; derivatives: no; redistribution: conditional; no derivatives | none | Link only | 2026-11-13 |
| [国家标准全文公开系统（含卫生健康类国家标准）](https://mdexa.com/datasets/openstd-national-standards/) | `restricted` | LicenseRef-all-rights-reserved; commercial use: unverified; derivatives: no; redistribution: no | none | Link only | 2026-11-12 |

## Drug lists and formularies

| Dataset | license_status | Main conditions | Risk flags | Access | Last verified |
|---|---|---|---|---|---|
| [国家基本医疗保险、生育保险和工伤保险药品目录（2025年）](https://mdexa.com/datasets/nrdl-2025/) | `unverifiable` | n/a (no license conclusion) | none | Link only | 2026-11-12 |

## Open models

A model has two licenses: one for the code and one for the weights. They are listed separately and never merged.

| Model | Code license | Weights license | Weights conditions | Access | Last verified |
|---|---|---|---|---|---|
| [AlphaFold 3](https://mdexa.com/models/alphafold3/) | `permissive` (Apache-2.0) | `restricted` (LicenseRef-Google-DeepMind-terms) | commercial use: no; derivatives: unstated; redistribution: no; registration required; depends on territory; keep notices; attribution | Registration required | 2026-11-14 |
| [Boltz (Boltz-1 and Boltz-2)](https://mdexa.com/models/boltz/) | `permissive` (MIT) | `permissive` (MIT) | keep notices | Public | 2026-11-14 |
| [ESM C](https://mdexa.com/models/esm-c/) | `permissive` (MIT) | `unverifiable` | n/a (no license conclusion) | Public | 2026-11-14 |
| [ESM-2](https://mdexa.com/models/esm2/) | `permissive` (MIT) | `permissive` (MIT) | keep notices | Public | 2026-11-14 |
| [ESM3 open (esm3-sm-open-v1)](https://mdexa.com/models/esm3-open/) | `permissive` (MIT) | `permissive` (MIT) | keep notices | Public | 2026-11-14 |
| [ESMFold](https://mdexa.com/models/esmfold/) | `permissive` (MIT) | `permissive` (MIT) | keep notices | Public | 2026-11-14 |
| [Evo 2](https://mdexa.com/models/evo2/) | `permissive` (Apache-2.0) | `permissive` (Apache-2.0) | keep notices | Public | 2026-11-14 |
| [OpenFold3](https://mdexa.com/models/openfold3/) | `permissive` (Apache-2.0) | `permissive` (Apache-2.0) | keep notices | Credentialed | 2026-11-14 |

## How to read this list

- `license_status` is what the sources state: `permissive`, `restricted`, `conflict`, `unstated` or `unverifiable`.
- **(flagged)**: a permissive license with source risk flags. That is not a clean bill: check the flags (for example `exam-derived`, `scraped`, `real-patient-text`) before use.
- **(repo license only)**: only the code repository carries a license. A repository license is not a data license.
- **(unsigned)**: a person has not signed this verdict, so it is read strictly. Where the automatic review reached a stricter conclusion, that conclusion is shown first and the published one after it; the card explains why.
- **Main conditions**: the license identifier, any right that is not a plain yes, and the recorded conditions. For `conflict`, `unstated` and `unverifiable` there is no license conclusion, so conditions do not apply.
- **Access**: Public (the source lists open files, or states that no account is needed), Registration required (the source asks for an account, a registration or a subscription), Credentialed (the source requires an application or approval), Link only (Mdexa records the official link but no access path; follow the source).
- Entries that are only registered and not yet verified are not listed.

## About this list

- Source: the verified records of the [Mdexa database](https://mdexa.com); the open snapshot is [mdexa-ai/mdexa-ai-native-database](https://github.com/mdexa-ai/mdexa-ai-native-database). Each row links to its card, which carries the quoted evidence, the dates and the change log.
- To add a dataset, see [CONTRIBUTING.md](CONTRIBUTING.md). Rows are generated, so pull requests that edit them are not merged by hand.
- This list is published under CC BY 4.0 (see [LICENSE](LICENSE)). Each dataset and model keeps its own license.
- Not legal advice: rows state what the sources say on the dates shown. Check the original source before use.
