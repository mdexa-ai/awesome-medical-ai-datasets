# Awesome Medical AI Datasets（医学 AI 数据集清单）

医学 AI 数据集与开放模型，按领域分节。每行给出许可结论、主要条件、来源风险标记和获取方式，并链接到 [Mdexa 数据库](https://mdexa.com) 中带日期、附来源原文的记录。本清单由这些记录生成，每次数据发布时重新生成；当前收录规模见 https://mdexa.com/v1/stats 。

Other languages: [English](README.md)

## 目录

- [临床医学](#临床医学)
- [药学与药物](#药学与药物)
- [基因与组学](#基因与组学)
- [生物医学文献](#生物医学文献)
- [中医药](#中医药)
- [标准与术语](#标准与术语)
- [药品目录](#药品目录)
- [开放模型](#开放模型)
- [怎么读这份清单](#怎么读这份清单)
- [关于本清单](#关于本清单)

## 临床医学

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [BianQueCorpus（扁鹊健康大数据）](https://mdexa.com/datasets/bianque-corpus/) | `restricted` | LicenseRef-THUDM-ChatGLM-6B-Model-License; 商用: 否; 改编: 未核实; 再分发: 未核实 | derived, scraped, real-patient-text | 仅链接 | 2026-11-12 |
| [CBLUE](https://mdexa.com/datasets/cblue/) | `unstated` (仅有仓库许可) | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |
| [ChatMed_Consult_Dataset](https://mdexa.com/datasets/chatmed-consult-dataset/) | `conflict` (未经人签) | 未经人签，见信息卡 | scraped, model-generated | 公开 | 2026-11-12 |
| [Chinese-medical-dialogue-data（Toyhom）](https://mdexa.com/datasets/chinese-medical-dialogue-data/) | `permissive` (有风险标记) | MIT | unknown-provenance | 仅链接 | 2026-11-12 |
| [ClinicalTrials.gov](https://mdexa.com/datasets/clinicaltrials-gov/) | `unstated` | 不适用（无许可结论） | 无 | 公开 | 2026-11-13 |
| [ClinPGx/PharmGKB](https://mdexa.com/datasets/pharmgkb/) | `restricted` | LicenseRef-Stanford-University-terms; 商用: 否; 改编: 有条件; 再分发: 有条件; 署名; 相同方式共享; 保留声明 | 无 | 仅链接 | 2026-11-13 |
| [CMB (Chinese Medical Benchmark)](https://mdexa.com/datasets/cmb/) | `permissive` (有风险标记) | Apache-2.0 | exam-derived | 公开 | 2026-11-12 |
| [cMedQA2](https://mdexa.com/datasets/cmedqa2/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | 无 | 仅链接 | 2026-11-12 |
| [CMExam](https://mdexa.com/datasets/cmexam/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | exam-derived | 公开 | 2026-11-12 |
| [CMKG（中文多模态医学知识图谱）](https://mdexa.com/datasets/cmkg/) | `unstated` | 不适用（无许可结论） | scraped | 仅链接 | 2026-11-12 |
| [CMtMedQA](https://mdexa.com/datasets/cmtmedqa/) | `permissive` (有风险标记) | MIT | real-patient-text | 公开 | 2026-11-12 |
| [DiagnosisArena](https://mdexa.com/datasets/diagnosisarena/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | real-patient-text | 公开 | 2026-11-14 |
| [DiaKG（糖尿病知识图谱标注数据）](https://mdexa.com/datasets/diakg/) | `unverifiable` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |
| [DISC-Med-SFT](https://mdexa.com/datasets/disc-med-sft/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | derived, scraped, real-patient-text, model-generated | 公开 | 2026-11-12 |
| [EgoExOR: An Egocentric–Exocentric Operating Room Dataset for Comprehensive Understanding of Surgical Activities](https://mdexa.com/datasets/egoexor/) | `permissive` | Apache-2.0; 保留声明 | 无 | 公开 | 2026-11-14 |
| [ESL-bench (Event-driven Synthetic Longitudinal Benchmark)](https://mdexa.com/datasets/esl-bench/) | `conflict` (未经人签) | 未经人签，见信息卡 | 无 | 仅链接 | 2026-11-14 |
| [GBaker/MedQA-USMLE-4-options-hf](https://mdexa.com/datasets/medqa-usmle-4-options-hf/) | `permissive` (有风险标记) | CC-BY-SA-4.0; 署名; 相同方式共享 | exam-derived | 公开 | 2026-11-14 |
| [HealthBench](https://mdexa.com/datasets/healthbench/) | `permissive` | MIT; 保留声明 | 无 | 公开 | 2026-11-14 |
| [huatuo_encyclopedia_qa](https://mdexa.com/datasets/huatuo-encyclopedia-qa/) | `permissive` (有风险标记) | Apache-2.0 | scraped | 公开 | 2026-11-12 |
| [Huatuo_knowledge_graph_qa](https://mdexa.com/datasets/huatuo-knowledge-graph-qa/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | derived | 公开 | 2026-11-14 |
| [Huatuo-26M](https://mdexa.com/datasets/huatuo-26m/) | `permissive` (有风险标记) | Apache-2.0 | scraped, real-patient-text | 仅链接 | 2026-11-12 |
| [Huatuo-Llama-Med-Chinese 知识库问答与文献数据](https://mdexa.com/datasets/huatuo-llama-med-chinese-data/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | model-generated | 仅链接 | 2026-11-12 |
| [Huatuo26M-Lite](https://mdexa.com/datasets/huatuo26m-lite/) | `permissive` (有风险标记) | Apache-2.0 | scraped, model-generated, derived | 公开 | 2026-11-12 |
| [huatuo26M-testdatasets](https://mdexa.com/datasets/huatuo26m-testdatasets/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | derived, real-patient-text | 公开 | 2026-11-14 |
| [HuatuoGPT-sft-data-v1](https://mdexa.com/datasets/huatuogpt-sft-data-v1/) | `permissive` (有风险标记) | Apache-2.0 | unknown-provenance | 公开 | 2026-11-12 |
| [HuatuoGPT2-Pretraining-Instruction](https://mdexa.com/datasets/huatuogpt2-pretraining-instruction/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | model-generated | 公开 | 2026-11-14 |
| [HuatuoGPT2-SFT-GPT4-140K](https://mdexa.com/datasets/huatuogpt2-sft-gpt4-140k/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | derived, model-generated | 公开 | 2026-11-14 |
| [IMCS-21](https://mdexa.com/datasets/imcs-21/) | `unstated` | 不适用（无许可结论） | real-patient-text | 仅链接 | 2026-11-12 |
| [INCLUDE](https://mdexa.com/datasets/include-base-44/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | exam-derived | 公开 | 2026-11-14 |
| [International Clinical Trials Registry Platform (ICTRP)](https://mdexa.com/datasets/who-ictrp/) | `restricted` | LicenseRef-WHO-terms; 商用: 有条件; 改编: 有条件; 再分发: 有条件; 署名 | 无 | 仅链接 | 2026-11-14 |
| [MedBench（上海人工智能实验室）](https://mdexa.com/datasets/medbench/) | `unverifiable` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |
| [MedDG](https://mdexa.com/datasets/meddg/) | `unstated` (仅有仓库许可) | 不适用（无许可结论） | scraped, real-patient-text | 仅链接 | 2026-11-12 |
| [MedDialog-CN](https://mdexa.com/datasets/meddialog-cn/) | `unverifiable` | 不适用（无许可结论） | scraped, real-patient-text | 仅链接 | 2026-11-12 |
| [medical-o1-reasoning-SFT（中文子集）](https://mdexa.com/datasets/medical-o1-reasoning-sft/) | `permissive` (有风险标记) | Apache-2.0 | model-generated | 公开 | 2026-11-12 |
| [Medical-Reasoning-SFT-Mega](https://mdexa.com/datasets/medical-reasoning-sft-mega/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | model-generated | 公开 | 2026-11-14 |
| [MedMCQA](https://mdexa.com/datasets/medmcqa/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | exam-derived, scraped | 公开 | 2026-11-14 |
| [medmcqa-es](https://mdexa.com/datasets/medmcqa-es/) | `permissive` (有风险标记) | CC-BY-4.0; 署名 | derived | 公开 | 2026-11-14 |
| [MedQA (USMLE 4-option, US subset + English textbook corpus)](https://mdexa.com/datasets/medqa-2/) | `permissive` (有风险标记) | MIT; 保留声明 | derived, exam-derived | 公开 | 2026-11-14 |
| [MedQA-USMLE-4-options](https://mdexa.com/datasets/medqa-usmle-4-options/) | `permissive` (有风险标记) | CC-BY-4.0; 署名 | exam-derived | 公开 | 2026-11-14 |
| [MedQA（含大陆中文题，MCMLE）](https://mdexa.com/datasets/medqa/) | `unstated` (仅有仓库许可) | 不适用（无许可结论） | exam-derived | 仅链接 | 2026-11-12 |
| [MLEC-QA](https://mdexa.com/datasets/mlec-qa/) | `unstated` (仅有仓库许可) | 不适用（无许可结论） | exam-derived | 仅链接 | 2026-11-12 |
| [PMC-Patients-ReCDS](https://mdexa.com/datasets/pmc-patients-recds/) | `restricted` | CC-BY-NC-SA-4.0; 商用: 否; 改编: 未声明; 再分发: 未声明; 署名; 相同方式共享 | derived, real-patient-text | 公开 | 2026-11-14 |
| [PromptCBLUE](https://mdexa.com/datasets/promptcblue/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | derived | 仅链接 | 2026-11-12 |
| [QASystemOnMedicalKG（医疗知识图谱）](https://mdexa.com/datasets/qasystem-medical-kg/) | `restricted` | 商用: 否; 改编: 未声明; 再分发: 未声明 | scraped | 仅链接 | 2026-11-12 |
| [R2MED Benchmark](https://mdexa.com/datasets/medqa-diag/) | `unstated` (未经人签; 公布结论 `permissive`) | 未经人签，见信息卡 | derived, exam-derived | 公开 | 2026-11-14 |
| [医学考试题库 JSON 数据集](https://mdexa.com/datasets/medical-exam-question-bank-json/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | exam-derived | 仅链接 | 2026-11-14 |

## 药学与药物

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [ATC/DDD Index](https://mdexa.com/datasets/atc-ddd/) | `restricted` | LicenseRef-WHO-Collaborating-Centre-for-Drug-Statistics-Methodology-terms; 商用: 否; 改编: 否; 再分发: 有条件; 署名; 禁止改编 | 无 | 仅链接 | 2026-11-14 |
| [BindingDB](https://mdexa.com/datasets/bindingdb/) | `permissive` (有风险标记) | CC-BY-3.0; 署名; 相同方式共享 | derived | 仅链接 | 2026-11-14 |
| [ChEMBL](https://mdexa.com/datasets/chembl/) | `permissive` | CC-BY-SA-3.0; 署名; 相同方式共享 | 无 | 仅链接 | 2026-11-14 |
| [DDInter](https://mdexa.com/datasets/ddinter/) | `restricted` | LicenseRef-all-rights-reserved; 商用: 未声明; 改编: 未声明; 再分发: 未声明 | 无 | 仅链接 | 2026-11-14 |
| [DrugBank](https://mdexa.com/datasets/drugbank/) | `restricted` | LicenseRef-OMx-Personal-Health-Analytics-DrugBank-terms; 商用: 否; 改编: 未声明; 再分发: 未声明; 需注册 | 无 | 需注册 | 2026-11-13 |
| [DrugCentral](https://mdexa.com/datasets/drugcentral/) | `unstated` | 不适用（无许可结论） | real-patient-text | 仅链接 | 2026-11-14 |
| [jablonkagroup/chempile-lift](https://mdexa.com/datasets/chempile-lift/) | `restricted` | CC-BY-NC-SA-4.0; 商用: 否; 改编: 未声明; 再分发: 未声明; 署名; 相同方式共享 | 无 | 仅链接 | 2026-11-14 |
| [openFDA](https://mdexa.com/datasets/openfda/) | `restricted` | LicenseRef-U-S-Food-and-Drug-Administration-terms; 商用: 有条件; 改编: 有条件; 再分发: 有条件; 署名 | 无 | 仅链接 | 2026-11-13 |
| [PubChem](https://mdexa.com/datasets/pubchem/) | `permissive` (未经人签) | 未经人签，见信息卡 | 无 | 仅链接 | 2026-11-14 |
| [RxNorm](https://mdexa.com/datasets/rxnorm/) | `restricted` | LicenseRef-National-Library-of-Medicine-terms; 商用: 有条件; 改编: 未声明; 再分发: 有条件; 保持最新 | derived | 仅链接 | 2026-11-13 |
| [THEMol: Torsion, Hessian, Energy of Molecules](https://mdexa.com/datasets/themol/) | `restricted` | CC-BY-NC-4.0; 商用: 否; 改编: 未声明; 再分发: 未声明; 署名 | 无 | 公开 | 2026-11-14 |
| [Therapeutics Data Commons](https://mdexa.com/datasets/tdc/) | `unstated` (仅有仓库许可) | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-14 |
| [TopU-LBVS: Multi-Target Benchmark for Ligand-Based Virtual Screening](https://mdexa.com/datasets/topu-lbvs/) | `permissive` (有风险标记) | CC-BY-SA-4.0; 署名; 相同方式共享; 保留声明 | derived | 仅链接 | 2026-11-14 |

## 基因与组学

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [AlphaFold Protein Structure Database](https://mdexa.com/datasets/alphafold-db/) | `permissive` (有风险标记) | CC-BY-4.0; 署名 | derived, model-generated | 仅链接 | 2026-11-14 |
| [GEO](https://mdexa.com/datasets/geo/) | `unstated` | 不适用（无许可结论） | 无 | 公开 | 2026-11-14 |
| [gnomAD](https://mdexa.com/datasets/gnomad/) | `restricted` (未经人签; 公布结论 `permissive`) | 未经人签，见信息卡 | 无 | 公开 | 2026-11-13 |
| [GTEx](https://mdexa.com/datasets/gtex/) | `unstated` | 不适用（无许可结论） | real-patient-text | 仅链接 | 2026-11-14 |
| [KEGG: Kyoto Encyclopedia of Genes and Genomes](https://mdexa.com/datasets/kegg/) | `restricted` | LicenseRef-Kanehisa-Laboratories-terms; 商用: 有条件; 改编: 未声明; 再分发: 有条件 | 无 | 需注册 | 2026-11-14 |
| [RCSB Protein Data Bank](https://mdexa.com/datasets/rcsb-pdb/) | `permissive` | CC0-1.0; 署名; 保留声明 | 无 | 仅链接 | 2026-11-14 |
| [Reactome](https://mdexa.com/datasets/reactome/) | `permissive` (未经人签) | 未经人签，见信息卡 | 无 | 仅链接 | 2026-11-14 |
| [STRING](https://mdexa.com/datasets/string/) | `permissive` (未经人签) | 未经人签，见信息卡 | 无 | 仅链接 | 2026-11-14 |
| [UniProt](https://mdexa.com/datasets/uniprot/) | `permissive` | CC-BY-4.0; 署名 | 无 | 仅链接 | 2026-11-13 |

## 生物医学文献

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [PubMed](https://mdexa.com/datasets/pubmed-medline/) | `unstated` | 不适用（无许可结论） | derived | 仅链接 | 2026-11-13 |
| [PubMedCausal](https://mdexa.com/datasets/pubmedcausal/) | `unstated` (未经人签; 公布结论 `permissive`) | 未经人签，见信息卡 | derived | 公开 | 2026-11-14 |
| [PubMedQA](https://mdexa.com/datasets/pubmedqa/) | `unstated` (未经人签; 公布结论 `permissive`) | 未经人签，见信息卡 | derived | 公开 | 2026-11-14 |

## 中医药

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [Chinese Herbal Medicine Sentiment Analysis Dataset](https://mdexa.com/datasets/chinese-herbal-medicine-sentiment/) | `permissive` (有风险标记) | MIT; 署名; 保留声明 | scraped | 公开 | 2026-11-14 |
| [Collection of 791 Traditional Chinese Medicine books（Figshare）](https://mdexa.com/datasets/figshare-tcm-791-books/) | `unverifiable` | 不适用（无许可结论） | derived | 仅链接 | 2026-11-12 |
| [HERB（中药高通量实验与文献数据库）](https://mdexa.com/datasets/herb/) | `unverifiable` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |
| [HWTCM（Haiwei 中医评测集）](https://mdexa.com/datasets/hwtcm/) | `permissive` (有风险标记) | MIT | unknown-provenance | 公开 | 2026-11-12 |
| [LingLanMedBench Traditional Chinese Medicine Benchmark Dataset](https://mdexa.com/datasets/linglan/) | `permissive` (有风险标记) | CC-BY-4.0; 署名; 保留声明 | exam-derived | 公开 | 2026-11-14 |
| [MedChatZH](https://mdexa.com/datasets/medchatzh/) | `conflict` (未经人签) | 未经人签，见信息卡 | 无 | 公开 | 2026-11-14 |
| [ShenNong_TCM_Dataset（ChatMed_TCM_Dataset）](https://mdexa.com/datasets/shennong-tcm-dataset/) | `conflict` (未经人签) | 未经人签，见信息卡 | model-generated | 公开 | 2026-11-12 |
| [TCM-3CEval](https://mdexa.com/datasets/tcm-3ceval/) | `unverifiable` | 不适用（无许可结论） | exam-derived | 仅链接 | 2026-11-12 |
| [tcm-acupuncture-classics（中医针灸经络古籍整理）](https://mdexa.com/datasets/tcm-acupuncture-classics/) | `restricted` | LicenseRef-wangekxy-commercial; 商用: 有条件; 改编: 未核实; 再分发: 否 | 无 | 公开 | 2026-11-12 |
| [TCM-Ladder](https://mdexa.com/datasets/tcm-ladder/) | `permissive` (有风险标记) | CC-BY-4.0 | exam-derived, scraped | 公开 | 2026-11-12 |
| [TCM-NER（中医药说明书实体识别）](https://mdexa.com/datasets/tcm-ner/) | `unverifiable` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |
| [TCM-SD（辨证分型数据集）](https://mdexa.com/datasets/tcm-sd/) | `unverifiable` | 不适用（无许可结论） | real-patient-text | 仅链接 | 2026-11-12 |
| [TCM-Text-Exams（ShizhenGPT 文本评测）](https://mdexa.com/datasets/tcm-text-exams/) | `permissive` (有风险标记) | Apache-2.0 | exam-derived | 公开 | 2026-11-12 |
| [TCM-Vision-Benchmark](https://mdexa.com/datasets/tcm-vision-benchmark/) | `permissive` (有风险标记) | Apache-2.0 | unknown-provenance | 公开 | 2026-11-12 |
| [TCMBench（TCM-ED）](https://mdexa.com/datasets/tcmbench/) | `unstated` | 不适用（无许可结论） | exam-derived | 仅链接 | 2026-11-12 |
| [TCMEval-SDT（辨证思维评测）](https://mdexa.com/datasets/tcmeval-sdt/) | `unverifiable` | 不适用（无许可结论） | real-patient-text | 仅链接 | 2026-11-12 |
| [TCMQA（TechTCM）](https://mdexa.com/datasets/tcmqa/) | `restricted` | CC-BY-NC-SA-4.0; 商用: 否; 改编: 有条件; 再分发: 有条件 | exam-derived | 公开 | 2026-11-12 |
| [tmmlu++](https://mdexa.com/datasets/tmmluplus/) | `permissive` (有风险标记) | MIT; 保留声明 | unknown-provenance | 公开 | 2026-11-14 |
| [Traditional Chinese Medicine Examination](https://mdexa.com/datasets/tcmle/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | exam-derived | 公开 | 2026-11-14 |
| [Traditional-Chinese-Medicine-Dataset-Pretrain](https://mdexa.com/datasets/traditional-chinese-medicine-dataset-pretrain/) | `permissive` (有风险标记) | Apache-2.0; 保留声明 | real-patient-text, scraped | 公开 | 2026-11-14 |
| [中医药多维知识图谱（TCM-MKG）](https://mdexa.com/datasets/tcm-mkg/) | `restricted` | CC-BY-NC-4.0; 商用: 否; 改编: 有条件; 再分发: 有条件 | derived | 公开 | 2026-11-12 |
| [殆知阁古代文献 txt 大全集（含医藏）](https://mdexa.com/datasets/daizhige-classics/) | `unstated` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |

## 标准与术语

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [Human Phenotype Ontology](https://mdexa.com/datasets/hpo/) | `restricted` | LicenseRef-Human-Phenotype-Ontology-Consortium-terms; 商用: 未声明; 改编: 否; 再分发: 未声明; 禁止改编; 保留声明; 注明改动 | 无 | 仅链接 | 2026-11-13 |
| [ICD-11](https://mdexa.com/datasets/icd-11/) | `restricted` | CC-BY-ND-3.0-IGO; 商用: 未声明; 改编: 否; 再分发: 未声明; 署名; 禁止改编 | 无 | 仅链接 | 2026-11-14 |
| [LOINC](https://mdexa.com/datasets/loinc/) | `restricted` | LicenseRef-Regenstrief-Institute-Inc-terms; 商用: 有条件; 改编: 有条件; 再分发: 有条件; 保留声明 | 无 | 仅链接 | 2026-11-14 |
| [MedDRA](https://mdexa.com/datasets/meddra/) | `restricted` | LicenseRef-MSSO-terms; 商用: 有条件; 改编: 未声明; 再分发: 未声明 | 无 | 需注册 | 2026-11-13 |
| [SNOMED CT](https://mdexa.com/datasets/snomed-ct/) | `restricted` | LicenseRef-SNOMED-International-terms; 商用: 有条件; 改编: 未声明; 再分发: 有条件; 依地区而定; 需注册 | 无 | 需注册 | 2026-11-14 |
| [UMLS Metathesaurus](https://mdexa.com/datasets/umls/) | `restricted` | LicenseRef-National-Library-of-Medicine-terms; 商用: 未声明; 改编: 否; 再分发: 有条件; 禁止改编 | 无 | 仅链接 | 2026-11-13 |
| [国家标准全文公开系统（含卫生健康类国家标准）](https://mdexa.com/datasets/openstd-national-standards/) | `restricted` | LicenseRef-all-rights-reserved; 商用: 未核实; 改编: 否; 再分发: 否 | 无 | 仅链接 | 2026-11-12 |

## 药品目录

| 数据集 | license_status | 主要条件 | 风险标记 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [国家基本医疗保险、生育保险和工伤保险药品目录（2025年）](https://mdexa.com/datasets/nrdl-2025/) | `unverifiable` | 不适用（无许可结论） | 无 | 仅链接 | 2026-11-12 |

## 开放模型

模型有两份许可：代码许可和权重许可。两栏分开列，从不合并。

| 模型 | 代码许可 | 权重许可 | 权重条件 | 获取方式 | 最近核实 |
|---|---|---|---|---|---|
| [AlphaFold 3](https://mdexa.com/models/alphafold3/) | `permissive` (Apache-2.0) | `restricted` (LicenseRef-Google-DeepMind-terms) | 商用: 否; 改编: 未声明; 再分发: 否; 需注册; 依地区而定; 保留声明; 署名 | 需注册 | 2026-11-14 |
| [Boltz (Boltz-1 and Boltz-2)](https://mdexa.com/models/boltz/) | `permissive` (MIT) | `permissive` (MIT) | 保留声明 | 公开 | 2026-11-14 |
| [ESM C](https://mdexa.com/models/esm-c/) | `permissive` (MIT) | `unverifiable` | 不适用（无许可结论） | 公开 | 2026-11-14 |
| [ESM-2](https://mdexa.com/models/esm2/) | `permissive` (MIT) | `permissive` (MIT) | 保留声明 | 公开 | 2026-11-14 |
| [ESM3 open (esm3-sm-open-v1)](https://mdexa.com/models/esm3-open/) | `permissive` (MIT) | `permissive` (MIT) | 保留声明 | 公开 | 2026-11-14 |
| [ESMFold](https://mdexa.com/models/esmfold/) | `permissive` (MIT) | `permissive` (MIT) | 保留声明 | 公开 | 2026-11-14 |
| [Evo 2](https://mdexa.com/models/evo2/) | `permissive` (Apache-2.0) | `permissive` (Apache-2.0) | 保留声明 | 公开 | 2026-11-14 |
| [OpenFold3](https://mdexa.com/models/openfold3/) | `permissive` (Apache-2.0) | `permissive` (Apache-2.0) | 保留声明 | 需资质 | 2026-11-14 |

## 怎么读这份清单

- `license_status` 记录来源怎么说：`permissive`、`restricted`、`conflict`、`unstated` 或 `unverifiable`。
- **(有风险标记)**：许可宽松，但带来源风险标记，不等于可以放心用；使用前先看标记（例如 `exam-derived`、`scraped`、`real-patient-text`）。
- **(仅有仓库许可)**：只有代码仓库带许可证。仓库许可不是数据许可。
- **(未经人签)**：这个结论还没有人签字，按更严的读法看待。自动复核得出更严结论的，先列更严结论，再列公布结论；原因见信息卡。
- **主要条件**：许可标识、不是简单「是」的权利项、已记录的条件。`conflict`、`unstated`、`unverifiable` 没有许可结论，条件不适用。
- **获取方式**：公开（来源列出了公开文件，或写明无需账号）、需注册（来源要求账号、注册或订阅）、需资质（来源要求申请或审批）、仅链接（Mdexa 记录了官方链接，未记录获取路径，以来源说明为准）。
- 只登记、尚未核实的条目不列入。

## 关于本清单

- 来源：[Mdexa 数据库](https://mdexa.com) 的已核实记录；公开快照见 [mdexa-ai/mdexa-ai-native-database](https://github.com/mdexa-ai/mdexa-ai-native-database)。每行链接到对应信息卡，卡上有来源原文引用、日期和修改记录。
- 要增加数据集，见 [CONTRIBUTING.md](CONTRIBUTING.md)。清单行由脚本生成，直接修改清单行的 pull request 不会被手工合并。
- 本清单以 CC BY 4.0 发布（见 [LICENSE](LICENSE)）。各数据集与模型保留各自的许可。
- 不构成法律意见：每行记录的是所示日期时各来源的说法，使用前请核对原始出处。
