# Complementary-Entity-Recognition
I work on Complementary Entity Recognition (CER) in the context of products, which is to identify products that can potentially work together. 


Hu Xu, Sihong Xie, Lei Shu, Philip S. Yu, CER: Complementary Entity Recognition via Knowledge Expansion on Large Unlabeled Product Reviews, IEEE International Conference on Big Data 2016 (IEEE Bigdata 2016)
https://arxiv.org/pdf/1612.01039v1.pdf

Here is the dataset used in my paper: 
https://www.cs.uic.edu/~hxu/CER_dataset.html

Usage:
```
import json
with open('CER_7.json', 'r) as f:
	products=json.load(f)	
#print the list of words of the 1st sentence in the first product.
print products[0]['X'][0]['words']
#print the list of labels of the 1st sentence in the first product.
print products[0]['y'][0]['label']
```

Citation:
```
@inproceedings{xu2016CER,
  title={CER: Complementary Entity Recognition via Knowledge Expansion on Large Unlabeled Product Reviews},
  author={Xu, Hu and Xie, Sihong and Shu, Lei and Yu, Philip S.},
  booktitle={Proceedings of IEEE International Conference on Big Data},
  year={2016}
}
```

