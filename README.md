# Barbie: Text to Barbie-Style 3D Avatars

[**Paper**](https://arxiv.org/abs/2403.09625) | [**Project Page**](https://liuff19.github.io/Make-Your-3D//) | [**Gallery**](https://drive.google.com/drive/folders/1FXDROWXrnsSQiOZ4vBgA_Yzib3irLNBc?usp=sharing)

Official implementation of Barbie: Text to Barbie-Style 3D Avatars

[Xiaokun Sun](https://scholar.google.com/citations?user=SG3SxqEAAAAJ), [Zhenyu Zhang](https://jessezhang92.github.io/), [Ying Tai](https://tyshiwo.github.io/index.html), Qian Wang, [Hao Tang](https://ha0tang.github.io/), [Zili Yi](https://zili-yi.github.io/), [Jian Yang](https://scholar.google.com.hk/citations?user=6CIDtZQAAAAJ), 


<p align="center"> All Code will be released soon... </p>

Abstract: Recent advances in text-guided 3D avatar generation have made substantial progress by distilling knowledge from diffusion models. Despite the plausible generated appearance, existing methods cannot achieve fine-grained disentanglement or high-fidelity modeling between inner body and outfit. In this paper, we propose Barbie, a novel framework for generating 3D avatars that can be dressed in diverse and high-quality Barbie-like garments and accessories. nstead of relying on a holistic model, Barbie achieves fine-grained disentanglement on avatars by semantic-aligned separated models for human body and outfits. These disentangled 3D representations are then optimized by different expert models to guarantee the domain-specific fidelity. To balance geometry diversity and reasonableness, we propose a series of losses for template-preserving and human-prior evolving. The final avatar is enhanced by unified texture refinement for superior texture consistency. Extensive experiments demonstrate that Barbie outperforms existing methods in both dressed human and outfit generation, supporting flexible apparel combination and animation.

<p align="center">
    <img src="assets/teaser.png">
</p>

## BibTeX

```bibtex
@misc{liu2024makeyour3d,
      title={Make-Your-3D: Fast and Consistent Subject-Driven 3D Content Generation}, 
      author={Fangfu Liu and Hanyang Wang and Weiliang Chen and Haowen Sun and Yueqi Duan},
      year={2024},
      eprint={2403.09625},
      archivePrefix={arXiv},
      primaryClass={cs.CV}
}
```
