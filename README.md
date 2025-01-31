## About the course

This repository is for use with the Pearson Publishing live webinar "Beginning Machine Learning with `scikit-learn`."  Versions of this material are used by other training provided by David Mertz and [KDM Training](http://kdm.training).

If you have attended one of the webinars using this material, I encourage you to complete the survey on it at: [Machine Learning with scikit-learn survey](https://goo.gl/pghpzD).  As folks fill this out, we will fold back the updated answers into the dataset used in the lessons themselves.

## Installing training materials

Before attending this course, please configure the environments you will need.  Within the repository, find the file `requirements.txt` to install software using `pip`, or the file `environment.yml` to install software using `conda`.  I.e.:

```bash
$ conda env create -f environment.yml
$ conda activate Pearson-ML
(Pearson-ML) $ jupyter notebook Outline.ipynb
```

Or

```bash
$ pip install -r requirements.txt
$ jupyter notebook Outline.ipynb
```

## Recommended reading

* [Beginner Machine Learning with `scikit-learn`](https://github.com/DavidMertz/ML-Live-Beginner)

* [Intermediate Machine Learning with `scikit-learn`](https://github.com/DavidMertz/ML-Live-Intermediate)

* [(Video) Machine Learning with scikit-learn LiveLessons](https://www.oreilly.com/library/view/machine-learning-with/9780135474198/), by David Mertz

* _Hands-On Machine Learning with Scikit-Learn and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems_, by Aurélien Géron

* _Deep Learning with Python_, by Francois Chollet

* _Introduction to Machine Learning with Python: A Guide for Data Scientists_, by by Andreas C. Müller & Sarah Guido 

* _Python Data Science Handbook: Essential Tools for Working with Data_, by Jake VanderPlas

* [Documentation of scikit-learn](https://scikit-learn.org/stable/documentation.html)
