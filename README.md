## Improved Block Merging for 3D Point Cloud Instance Segmentation

**The code will be released soon. Estimated time of arrival: 15 March 2024**

**Authors:** <a href="http://www.etrovub.be/LeonDenis" target="_blank">Leon Denis</a>, <a href="https://www.linkedin.com/in/remcoroyen/" target="_blank">Remco Royen</a>, and <a href="http://www.etrovub.be/AdrianMunteanu" target="_blank">Adrian Munteanu</a> - Vrije Universiteit Brussel (VUB). The second author has been funded by a FWO-SB scholarship.

### Introduction

This repository is the official code release of the work from our [conference paper](https://ieeexplore.ieee.org/document/10167976), published in 2023 24th International Conference on Digital Signal Processing (DSP).

This paper proposes a novel block merging algorithm suitable for any block-based 3D instance segmentation technique. The proposed work improves over the state-of-the-art by allowing wrongly labelled points of already processed blocks to be corrected through label propagation. By doing so, instance overlap between blocks is not anymore necessary to produce the desirable results, which is the main limitation of the current art. Our experiments show that the proposed block merging algorithm significantly and consistently improves the obtained accuracy for all evaluation metrics employed in literature, regardless of the underlying network architecture.

### Citation
If you find our work useful in your research, please consider citing:

  @inproceedings{denis2023improved,
    title={Improved Block Merging for 3D Point Cloud Instance Segmentation},
    author={Denis, Leon and Royen, Remco and Munteanu, Adrian},
    booktitle={2023 24th International Conference on Digital Signal Processing (DSP)},
    pages={1--5},
    year={2023},
    organization={IEEE}
  }
	
### License
Our code is released under MIT License (see LICENSE file for details).

## Contact
If you have any questions or suggestions regarding this repo or the paper, please feel free to contact me (remco.royen@vub.be).
