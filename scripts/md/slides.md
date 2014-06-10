title: Machine learning
subtitle: Basic problem setting

- Given: N samples of data
- Goal: predict properties of unseen data

![adaboost](images/plot_adaboost_twoclass_1.png)

---

title: What is scikit-learn?

- Simple and efficient tools for data mining and data analysis
- Built on NumPy, SciPy, and matplotlib
- Open source, BSD license
- Under active development


![](images/scikitlearn.png)

---

content_class: flexbox vcenter
class: image

![CPI predicted vs actual](images/ml_map_small.png)

---

title: Example - Support Vector Machine

<pre class="prettyprint" data-lang="python">
from sklearn import svm

train_X = ...  # load sample inputs
train_y = ...  # load sample outputs
to_predict = ...  # we want to predict the output of this value

clf = svm.SVC()  # create a classifier

clf.fit(train_X, train_y)  # train the classifier

prediction = clf.predict(to_predict)  # predict our unknown output
</pre>

<br>

[scikit-learn.org/stable/documentation.html](http://scikit-learn.org/stable/documentation.html)

---

title: scikit-learn @ Gallop Labs

- Optimization of Facebook campaigns
- Regression to predict certain outputs of a campaign

![Goals dashboard](images/goals_dashboard2.png)
![Audience breakdown](images/audience_breakdown2.png)

---

title: CPI predictions
content_class: flexbox vcenter
class: image

![CPI predicted vs actual](images/cpi_predicted_vs_actual.png)

