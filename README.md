# Deep_Ensemble_CNN_for_Imbalance_Labels

This is an example code of deep ensemble learning for overcoming imbalance labe. For more details, please refer to the the paper below.

Pfister, Franz MJ et al. "High-Resolution Motor State Detection in Parkinson's Disease Using Convolutional Neural Networks", Scientific Report. (under review)

Um, Terry Taewoong, et al. Parkinson's Disease Assessment from a Wrist-Worn Wearable Sensor in Free-Living Conditions: Deep Ensemble Learning and Visualization. arXiv preprint arXiv:1808.02870, 2018. [[arXiv]](https://arxiv.org/abs/1808.02870)

In the paper mentioned, we used real-world wearable sensor data collected from 30 Parkinson's patients. Since we are not able to make patient data available in public, we released an example code that works with MNIST data. You can run our example code with [Google Colab](https://colab.research.google.com/)

## Dependency
You need to first download rotated MNIST dataset from [here](https://sites.google.com/a/lisa.iro.umontreal.ca/public_static_twiki/variations-on-the-mnist-digits) and save it on your Google Drive. Our example code will download rotated MNIST dataset from your google drive, and also, save trained models to your google drive.

## License
You can freely modify this code for your own purpose. However, please leave the citation information untouched when you redistributed the code to others. If this code helps your research, please cite the paper.

```
@article{TerryUm_EnsembleCNN2018,
  author    = {Terry Taewoong Um and
               Franz Michael Josef Pfister and
               Daniel Christian Pichler and
               Satoshi Endo and
               Muriel Lang and
               Sandra Hirche and
               Urban Fietzek and
               Dana Kulic},
  title     = {Parkinson's Disease Assessment from a Wrist-Worn Wearable Sensor in
               Free-Living Conditions: Deep Ensemble Learning and Visualization},
  journal   = {CoRR},
  volume    = {abs/1808.02870},
  year      = {2018},
  url       = {http://arxiv.org/abs/1808.02870},
  archivePrefix = {arXiv},
  eprint    = {1808.02870},
  timestamp = {Sun, 02 Sep 2018 15:01:54 +0200},
  biburl    = {https://dblp.org/rec/bib/journals/corr/abs-1808-02870},
  bibsource = {dblp computer science bibliography, https://dblp.org}
}
```
