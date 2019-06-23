# logistic-regression-with-Donorchoose-dataset


In this project I have applied `logistic regression algorithm` on DonorChoose dataset to predict whether a given project will be approved funding or not.<br>

I have created 4 dataset. Each dataset contains text features encoded with different encoding techniques.<br>
**Set1** | Text features encoded with simple `Bag of words` vectorizer.<br>
**Set2** | Text Features encoded with `TFIDF` vectorizer.<br>
**Set3** | Text features encoded with `Avarage Word2Vec` vectorizer.<br>
**Set4** | Text features encoded with `TFIDF Word2Vec` vectorizer.<br>

Then LR is applied on all 4 datasets.<br>

<b> Conclusion after applying LR to all datasets </b><br>

`LR` is able to predict fund approval for project with 0.72 `AUC score` with `Set 2`. With `1/3` point is miss classified as `False positive` and `1/2` points are miss classified as `False Negative`.

##### Credits : www.AppliedAICourse.com
