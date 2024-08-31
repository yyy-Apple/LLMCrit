# LLMCrit
Here are the resources for ACL 2024 paper [LLMCRIT: Teaching Large Language Models to Use Criteria](https://arxiv.org/abs/2403.01069). We provide 
- Criteria together with constructed demonstrations for three tasks in `criteria_with_demonstrations` folder
- Our constructed test data for three tasks in `test_data` folder

# Bib
Please cite our work if you find it useful.
```text
@inproceedings{yuan-etal-2024-llmcrit,
    title = "{LLMC}rit: Teaching Large Language Models to Use Criteria",
    author = "Yuan, Weizhe  and
      Liu, Pengfei  and
      Gall{\'e}, Matthias",
    editor = "Ku, Lun-Wei  and
      Martins, Andre  and
      Srikumar, Vivek",
    booktitle = "Findings of the Association for Computational Linguistics ACL 2024",
    month = aug,
    year = "2024",
    address = "Bangkok, Thailand and virtual meeting",
    publisher = "Association for Computational Linguistics",
    url = "https://aclanthology.org/2024.findings-acl.472",
    pages = "7929--7960",
    abstract = "Humans follow criteria when they execute tasks, and these criteria are directly used to assess the quality of task completion. Therefore, having models learn to use criteria to provide feedback can help humans or models to perform tasks better. However, current research in this area tends to consider only a limited number of criteria, or only a limited number of quality assessment aspects. To fill this gap, we propose a general framework that enables large language models (LLMs) to use comprehensive criteria for a task in delivering natural language feedback on task execution. In particular, we present a model-in-the-loop framework that semi-automatically derives criteria from collected guidelines for different writing tasks and constructs in-context demonstrations for each criterion. We choose three tasks from real-world scenarios to operationalize this idea: paper introduction writing, Python code writing, and Reddit post writing, and evaluate our feedback generation framework using different LLMs. The results reveal the fine-grained effects of adding criteria and demonstrations and provide valuable guidance on how to teach LLMs to use criteria more effectively.",
}
```
