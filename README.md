# Art-Exhibition-Recommendation-System
We present  

## Data
The original source of our dataset is [WikiArt](https://www.wikiart.org/) and gathered from [here](https://github.com/cs-chan/ArtGAN/blob/master/WikiArt%20Dataset/README.md).
```
@article{artgan2018,
  title={Improved ArtGAN for Conditional Synthesis of Natural Image and Artwork},
  author={Tan, Wei Ren and Chan, Chee Seng and Aguirre, Hernan and Tanaka, Kiyoshi},
  journal={IEEE Transactions on Image Processing},
  volume    = {28},
  number    = {1},
  pages     = {394--409},
  year      = {2019},
  url       = {https://doi.org/10.1109/TIP.2018.2866698},
  doi       = {10.1109/TIP.2018.2866698}
}
```
The list of artworks and meta data that we used is available in ```data``` folder.

## Experiment
We built a website that gets real-time users’ preference on certain art images as inputs, and returns recommended art
images. The website refers a form of [TindART](https://dl.acm.org/doi/10.1145/3394171.3414445), a visual art recommendation system. When a user access the website, the recommendation results are provided with the following steps.

1. A user is provided with images of artwork sequentially, 20 in total. For each artwork, the user is to choose between ’like’ or ’dislike’ button.
2. After all choices have been made, the user is provided with two artwork recommendation sets; One close to his choice and the other recommended randomly.
3. A user is asked to fill out an online questionnaire to assess his satisfaction level on the recommendations.

<p align="center">
<img src=https://user-images.githubusercontent.com/97038307/218486020-545d4755-fa81-4159-aed5-81417080567f.png width=90%>
</p>
