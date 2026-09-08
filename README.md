**Extending Population-Level Trajectory Memory with Declarative Memory: A Fusion-Based Approach**

MSc project extending MATM's procedural trajectory memory with a novel declarative knowledge source (K2), combined via a fusion mechanism adapted from HF-RAG. Evaluated on ALFWorld.

**Contents**

MSc_project_2920686S.zip contains:

source_code/ — retrieval, fusion, and evaluation pipeline; K2 construction; learning-to-rank models

results_and_outputs/ — full per-episode evaluation logs (all conditions), statistical validation scripts and results






**Original Works Referenced**

**MATM** (procedural memory architecture, extended in this work):

@article{kim2026multiagenttransactivememory,
      title={Multi-Agent Transactive Memory}, 
      author={To Eun Kim and Xuhong He and Dishank Jain and Ambuj Agrawal and Negar Arabzadeh and Fernando Diaz},
      year={2026},
      eprint={2606.19911},
      archivePrefix={arXiv},
      primaryClass={cs.AI},
      url={https://arxiv.org/abs/2606.19911}, 
}


**HF-RAG** (fusion mechanism, adapted in this work):

@inproceedings{santra2025hfrag,
      title={HF-RAG: Hierarchical Fusion-based RAG with Multiple Sources and Rankers},
      author={Payel Santra and Madhusudan Ghosh and Debasis Ganguly and Partha Basuchowdhuri and Sudip Kumar Naskar},
      year={2025}, booktitle={Proceedings of CIKM '25},
      eprint={2509.02837}, archivePrefix={arXiv}, primaryClass={cs.IR},
      url={https://arxiv.org/abs/2509.02837},
}

**Dataset**

**ALFWorld** (evaluation environment and source of K1's training trajectories):

@inproceedings{ALFWorld20,
  title={{ALFWorld: Aligning Text and Embodied Environments for Interactive Learning}},
  author={Mohit Shridhar and Xingdi Yuan and Marc-Alexandre C\^ot\'e and Yonatan Bisk and Adam Trischler and Matthew Hausknecht},
  booktitle={Proceedings of the International Conference on Learning Representations (ICLR)},
  year={2021},
  url={https://arxiv.org/abs/2010.03768}
}
Repository of dataset: https://github.com/alfworld/alfworld
Huggingface link for dataset: https://huggingface.co/datasets/toeunkim/matm-trajectories/blob/main/alfworld/prepopulation.parquet
