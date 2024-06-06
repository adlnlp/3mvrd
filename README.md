# [3MVRD: Multimodal Multi-task Multi-teacher Visually-Rich Form Document Understanding](https://arxiv.org/abs/2402.17983)
This paper presents a groundbreaking multimodal, multi-task, multi-teacher joint-grained knowledge distillation model for visually-rich form document understanding. The model is designed to leverage insights from both fine-grained and coarse-grained levels by facilitating a nuanced correlation between token and entity representations, addressing the complexities inherent in form documents. Additionally, we introduce new intra-grained and cross-grained loss functions to further refine diverse multi-teacher knowledge distillation transfer process, presenting distribution gaps and a harmonised understanding of form documents. Through a comprehensive evaluation across publicly available form document understanding datasets, our proposed model consistently outperforms existing baselines, showcasing its efficacy in handling the intricate structures and content of visually complex form documents. 

#### <div align="center"> Yihao Ding, Lorenzo Vaiani, Soyeon Caren Han, Jean Lee, Paolo Garza, Josiah Poon, Luca Cagliero </div>
#### <div align="center"> Accepted by Findings of the Association for Computational Linguistics (ACL 2024) </div>
## Methodology
<p align="center"><img src="figures/mmm_architecture.png" width="750" /></p>

Our paper interprets visually rich documents, especially form documents collaboratively created and used by multiple parties. We employ two tiers of multimodal information: fine-grained and coarse-grained levels, crucial for understanding the structure and content of form pages. Existing pre-trained visual-language models often focus on one of these aspects. Our approach integrates knowledge from diverse models to enhance document understanding for downstream tasks.

## Datasets

## Reproducing

## Citation

If you use our work or dataset in your research, please cite our paper:

```bibtex
@article{ding2024m3,
  title={M3-VRD: Multimodal Multi-task Multi-teacher Visually-Rich Form Document Understanding},
  author={Ding, Yihao and Vaiani, Lorenzo and Han, Caren and Lee, Jean and Garza, Paolo and Poon, Josiah and Cagliero, Luca},
  journal={arXiv preprint arXiv:2402.17983},
  year={2024}
}


