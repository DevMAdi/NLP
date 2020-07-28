## Natural Language Programming

It's advisable to use .tsv(**Tab separated value**) file for review file nip.
-> as it is possible that customer may have put (,) in his review
& csv file would then read it as delimiter & we will get unwanted result.

Que. why **Cleaning** of texts & stemming required?
-> This is required as we're going to create Bag of Words model
![enter image description here](https://github.com/DevMAdi/NLP/blob/master/BoWBag-of-Words-model.PNG?raw=true)

if data not Cleaned- we will have huge **sparsity** in our model

**sparse matrix**- matrix which contains very few non-zero elements. When a sparse matrix is represented with a 2-dimensional array, we waste a lot of space to represent that matrix.

**Stemming** if not done. then Words such as love, loved, loving, will love etc. will have their own column. Thus sparse score will increase as they all have same meaning & should be treated as single entity.
