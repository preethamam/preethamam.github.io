---
title: "Cracks Classification"
excerpt: '<img src="/images/Dataset_3_Cracks-26.7K_(644x483)_crack.png" width="500" height="500" alt="Concrete and pavement cracks">'
collection: datasets
date: 2024-07-01
---

Cracks are the defects formed by cyclic loading, fatigue, shrinkage, creep, and so on. In addition, they represent the deterioration of the structures over some time. Therefore, it is essential to detect and classify them according to the condition grade at the early stages to prevent the collapse of structures. Deep learning and machine learning-based supervised classification methods requires carefully annotated images of cracks. This is a repository of human annotated classification datasets of concrete, pavement, walls/mixed and masonry/bricks cracks surface. I collected these datasets during my Ph.D. days and used many for my dissertation. The original [GitHub](https://github.com/preethamam/Cracks-Classification-Datasets) link.

## Datasets examples

| No. | Dataset name | Cracks images | Non-cracks images | Remarks |
|:-------:|:-------:|:-------:|:-------:|:-------:|
| 1 | [Cracks-5.7K (227x227)](https://1drv.ms/f/c/49b23bc11eecd6a8/EtBNtnET4YtFmuJCKQXWLRcBywLJiQy6tVR8nIw-a2hkZQ?e=f49fEx) | ![](/images/Dataset_1_Cracks-5.7K_(227x227)_crack.png) | ![](/images/Dataset_1_Cracks-5.7K_(227x227)_noncrack.png) | Concrete and pavement surface images. This dataset has a great variety with types of cracks and texture. Highly textureous and cracks width varies largely. Types of cracks include a few strands, branched and surface.| 
| 2 | [Cracks-3.7K (644x483)](https://1drv.ms/f/c/49b23bc11eecd6a8/ErWfsmYD6FdKof52qUiJ7hUBAVS50eAoo32WQJBDNPVzFw?e=IfcLua) | ![](/images/Dataset_2_Cracks-3.7K_(644x483)_crack.png) | ![](/images/Dataset_2_Cracks-3.7K_(644x483)_noncrack.png) | Purely a concrete surface images. This dataset has a cracks with a few strands and some branches. Highly textureous and cracks width varies largely. |
| 3 | [Cracks-26.7K (644x483)](https://1drv.ms/f/c/49b23bc11eecd6a8/ErI4bqgf_ClPujbQGGkq9RABmMnL0kt-0yuvPFMMqPBnUw?e=TyzvCw) | ![](/images/Dataset_3_Cracks-26.7K_(644x483)_crack.png) | ![](/images/Dataset_3_Cracks-26.7K_(644x483)_noncrack.png) | This is a mixture of concrete and pavement surface images. This dataset has a cracks with a few strands, some branches and surface types. Highly textureous and cracks width varies largely. |
| 4 | [Cracks-1.3K](https://1drv.ms/f/c/49b23bc11eecd6a8/Egqz7v0s5glAn8InjAHBfWIBK6Gwq-c5_afnr8C74RztMA?e=qpojee) | ![](/images/Dataset_4_Cracks-1.3K_crack.png) | ![](/images/Dataset_4_Cracks-1.3K_noncrack.png) | This dataset is the most diverse and consists of concrete, pavement, walls and glass surface images. This dataset has a cracks with a few strands, thin, thick, branched and surface. Highly textureous and cracks width varies largely. I call this dataset as ***The Wild Wild West*** because of its diversity and different images size. |

## Citation

All texture datasets are available to the public. If you use any of these datasets in your research, please use the following BibTeX entry to cite:
{% raw %}
```bibtex
@PhdThesis{preetham2021vision,
	author  = {Aghalaya Manjunatha, Preetham},
	title   = {Vision-Based and Data-Driven Analytical and Experimental Studies into Condition Assessment and Change Detection of Evolving Civil, Mechanical and Aerospace Infrastructures},
	school  = {University of Southern California},
	year    = {2021},
	type    = {Dissertations & Theses},
	address = {3550 Trousdale Parkway Los Angeles, CA 90089},
	month   = {December},
	note    = {Condition assessment, Crack localization, Crack change detection, Synthetic crack generation, Sewer pipe condition assessment, Mechanical systems defect detection and quantification}
}
```
{% endraw %}

## Acknowledgements

I thank Shravan Ravi, Vinay Hegde, and Milind Bhat (chronological order) for their efforts in the collection and preparation of the crack and non-crack image database around the University of Southern California (USC) campus at Los Angeles, USA. I thank Dr. Azarang Golmohammadi who web harvested crack images of concrete, pavement, walls, glass and non-crack images in [Cracks-1.3K](https://1drv.ms/f/c/49b23bc11eecd6a8/Egqz7v0s5glAn8InjAHBfWIBK6Gwq-c5_afnr8C74RztMA?e=qpojee) dataset. In addition, I thank Ryan, Milind and Ajay Kumar V. (chronological order) for their conscientious efforts in creating for crack and non-crack classification annotations.
