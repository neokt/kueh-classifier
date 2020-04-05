# Kueh Classifier

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/neokt/kueh-classifier/master?urlpath=%2Fvoila%2Frender%2Fkueh-classifier-widget.ipynb)

Prototype of an image classifier for fastai's DL 1v4 course.

<img src="kueh-classifier-screenshot.png" width=300>

[Link to Prototype on Binder](https://mybinder.org/v2/gh/neokt/kueh-classifier/master?urlpath=%2Fvoila%2Frender%2Fkueh-classifier-widget.ipynb)
(takes a few minutes to launch and render)

#### Instructions
Model trained using transfer learning on [ResNet-18](https://arxiv.org/pdf/1512.03385.pdf) with [fastai2](https://github.com/fastai/fastai2).

Training conducted on a Paperspace free GPU instance ([setup instructions](https://course.fast.ai/start_gradient.html)) and the Paperspace + Fast.Ai 2.0 (V4) container.

Prototype created using [ipywidgets](https://github.com/jupyter-widgets/ipywidgets), [Voilà](https://github.com/voila-dashboards/voila) and [Binder](https://mybinder.org/). 

See [Conda environment file](environment.yml) for dependencies.

#### What is Kueh?
While we’re lucky to have all sorts of gastronomical delights available to us in New York, I often find myself longing for the food and sweets of my homeland, Singapore. One sweet item that I miss dearly that I can’t find here is Nyonya Kueh (粿).

Kueh are sweet or savory snacks that can be traced back to Malaysia or Indonesia, and were adopted by the Peranakan Chinese community in Singapore. Coconut milk, pandan leaves, glutinous rice, and palm sugar are some of the common ingredients in Kueh.

Kueh come in all sorts of delightful colors, shapes, sizes and textures. Given the diverse nature of Kueh, it’d be interesting to prototype a Kueh classifier that we could use to identify all the different types that are out there! Besides identification, it’d also be interesting for the user to know what ingredients are in which Kueh (for example, if you are allergic to certain ingredients). Also, the intersection of data scientists and machine learning engineers who know what Kueh are is probably tiny, so it is highly unlikely that this problem has been tackled before!

