# Complementary-Entity-Recognition and Product Compatibility Analysis on QAs and Reviews
I work on Complementary Entity Recognition (CER) in the context of products reviews and QAs, which is to identify entities that can potentially work together. 
It's like aspect extraction and complementary entity is a special kind of aspect in the area of Aspect-Based Sentiment Analysis (ABSA), which is largely ignored in existing research!

Similar to aspect-based sentiment classification, we have a problem called Product Compatibility Analysis that further requires to classify whether the complementary entity is compatible or not. 

Product QA datasets are ideal datasets for such task, where such kinds of "aspect" may appear in the question and the compatibility info is in the answer. 

Here is the dataset used in my papers: 
https://www.cs.uic.edu/~hxu/QA_dataset.html
https://www.cs.uic.edu/~hxu/CER_dataset.html


Papers:
```
@inproceedings{Xu2018pro,
  title={Dual Attention Network for Product Compatibility and Function Satisfiability Analysis},
  author={Xu, Hu and Xie, Sihong and Shu, Lei and Yu, Philip S.},
  booktitle={Proceedings of AAAI Conference on Artificial Intelligence (AAAI)},
  year={2018}
}

@inproceedings{xu2016CER,
  title={CER: Complementary Entity Recognition via Knowledge Expansion on Large Unlabeled Product Reviews},
  author={Xu, Hu and Xie, Sihong and Shu, Lei and Yu, Philip S.},
  booktitle={Proceedings of IEEE International Conference on Big Data},
  year={2016}
}

@inproceedings{xu2017Fun,
  title={Product Function Need Recognition via Semi-supervised Attention Network},
  author={Xu, Hu and Xie, Sihong and Shu, Lei and Yu, Philip S.},
  booktitle={Proceedings of IEEE International Conference on Big Data},
  year={2017}
}
```

