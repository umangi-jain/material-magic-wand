# Material Magic Wand

Official repository for:

**Material Magic Wand: Material-Aware Grouping of 3D Parts in Untextured Meshes**  
Umangi Jain, Vladimir Kim, Matheus Gadelha, Igor Gilitschenski, Zhiqin Chen  
CVPR 2026

[Project Page](https://umangi-jain.github.io/material-magic-wand/)

## Status

Code release coming soon.

This repository is being prepared for public release. It will contain:

- training and evaluation code
- data processing scripts
- interactive demo tooling
- instructions for reproducing the paper results

## Abstract

We introduce the problem of material-aware part grouping in untextured meshes. Many real-world shapes contain repeated structures that share the same material but exhibit geometric variations. When assigning materials to such meshes, these repeated parts often require piece-by-piece manual identification and selection, which is tedious and time-consuming. To address this, we propose Material Magic Wand, a tool that allows artists to select part groups based on their estimated material properties. When one part is selected, our algorithm automatically retrieves all other parts likely to share the same material. The key component of our approach is a part encoder that generates a material-aware embedding for each 3D part, accounting for both local geometry and global context.

## Planned Release

The public release will include cleaned code, documentation, and setup instructions.

## Citation

```bibtex
@inproceedings{materialmagicwand2026,
  title={Material Magic Wand: Material-Aware Grouping of 3D Parts in Untextured Meshes},
  author={Jain, Umangi and Kim, Vladimir and Gadelha, Matheus and Gilitschenski, Igor and Chen, Zhiqin},
  booktitle={Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition},
  year={2026}
}
```

## Contact

For questions about the project, please use the project page for updates until the code is released.
