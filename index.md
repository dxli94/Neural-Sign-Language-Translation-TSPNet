## Welcome to TSPNet Homepage


Introduction
---------------
Sign language translation (SLT) aims to interpret sign video sequences into text-based natural language sentences. Sign videos consist of continuous sequences of sign gestures with no clear boundaries in between. Existing SLT models usually represent sign visual features in a frame-wise manner so as to avoid needing to explicitly segmenting the videos into isolated signs. However, these methods neglect the temporal information of signs and lead to substantial ambiguity in translation.

In this paper, we explore the temporal semantic structures of signvideos to learn more discriminative features. To this end, we first present a novel sign video segment representation which takes into account multiple temporal granularities, thus alleviating the need for accurate video segmentation. Taking advantage of the proposed segment representation, we develop a novel hierarchical sign video feature learning method via a temporal semantic pyramid network, called TSPNet. Specifically, TSPNet introduces an inter-scale attention to evaluate and enhance local semantic consistency of sign segments and an intra-scale attention to resolve semantic ambiguity by using non-local video context.

Experiments show that our TSPNet outperforms the state-of-the-art with significant improvements on the BLEU score (from 9.58 to 13.41) and ROUGE score (from 31.80 to 34.96)on the largest commonly-used SLT dataset.

<iframe width="1070" height="602" src="https://www.youtube.com/embed/-EAmcFrrRGk" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

[[Paper](https://proceedings.neurips.cc//paper/2020/file/8c00dee24c9878fea090ed070b44f1ab-Paper.pdf)] [[Poster](poster/main.pdf)] [[Code](https://github.com/verashira/TSPNet)] [[Video](https://www.youtube.com/watch?v=-EAmcFrrRGk)]

News
---------------
* <span style="color: red"><b>NEW:</b></span> Dec.17,2020  We have released the implementation of TSPNet [here](https://github.com/verashira/TSPNet), including codes, pre-trained weights and features - everything you need to replicate the reported results.



Citation
--------------

Please cite our papers as:
```bibtex
@inproceedings{li2020tspnet,
	title        = {TSPNet: Hierarchical Feature Learning via Temporal Semantic Pyramid for Sign Language Translation},
	author       = {Li, Dongxu and Xu, Chenchen and Yu, Xin and Zhang, Kaihao and Swift, Benjamin and Suominen, Hanna and Li, Hongdong},
	year         = 2020,
	booktitle    = {Advances in Neural Information Processing Systems},
	volume       = 33
}

@inproceedings{li2020word,
      title={Word-level Deep Sign Language Recognition from Video: A New Large-scale Dataset and Methods Comparison},
      author={Li, Dongxu and Rodriguez, Cristian and Yu, Xin and Li, Hongdong},
      booktitle={The IEEE Winter Conference on Applications of Computer Vision},
      pages={1459--1469},
      year={2020}
}
```
Other work you might be interested to look at.
```bibtex
@article{li2020transferring,
      title={Transferring Cross-domain Knowledge for Video Sign Language Recognition},
      author={Li, Dongxu and Yu, Xin and Xu, Chenchen and Petersson, Lars and Li, Hongdong},
      journal={arXiv preprint arXiv:2003.03703},
      year={2020}
}
```


Contacts
------------------
- [Dongxu Li](https://scholar.google.com.au/citations?user=h5XtaUUAAAAJ&hl=en&oi=ao): dongxu.li@anu.edu.au
- [Chenchen Xu](https://scholar.google.com.au/citations?user=01_mhZcAAAAJ&hl=en): chenchen.xu@anu.edu.au
