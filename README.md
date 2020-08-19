
# Are Vine Reviews truly trustworthy?

In Amazon's Vine program, reviewers receive free products in exchange for reviews.  
Review dataset: https://s3.amazonaws.com/amazon-reviews-pds/tsv/index.txt  

Amazon has several policies to reduce the bias of its Vine reviews: https://www.amazon.com/gp/vine/help?ie=UTF8.  
But are Vine reviews truly trustworthy? Your task is to investigate whether Vine reviews are free of bias.   

#### list of files
- level1a.ipynb : Google Colab notebook which loads video game reivews
- level1b.ipynb : Google Colab notebook which loads apparel reviews
- level2.ipynb  : Google Colab notebook which does the analysis


### Conclusion:
* Vine reviews in general have higher star ratings (4.03 > 3.80)
* Vine reviews have higher percentage of helpful votes. (74.7% > 72.0%)
* in short, Vine reviews are useful, but we should keep in mind that their ratings are usually higher than normal.