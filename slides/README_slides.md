---
jupyter:
  jupytext:
    text_representation:
      extension: .md
      format_name: myst
      format_version: '1.1'
      jupytext_version: 1.1.0
  kernelspec:
    display_name: Python 3
    language: python
    name: python3
---
<!-- 
+++ {"slideshow": {"slide_type": "slide"}}

# Tutorial slides

- Slides are optional (e.g., you may not use them if your presentation is via live coding).
- If the pre-recorded presentations will use slides, we request that you deposit the slides in this folder.

+++ {"slideshow": {"slide_type": "slide"}}

## Use text-based source

- We ask that you use text-based formats for your slides, e.g., markdown 
- This markdown file is an example source for slides using `nbconvert` and Reveal. See the GitHub action '.github/workflows/slides.yml' in this repo so see how this markdown file is converted to a HTML slide show and published on GitHub Pages - https://fawazsiddiqi.github.io/slides_to_pages

+++ {"slideshow": {"slide_type": "subslide"}}

## An example sub-slide

- Another option: you can write your slide content using markdown and use an app for slide design, like [Deckset](https://www.deckset.com) or similar.

+++ {"slideshow": {"slide_type": "slide"}}

## Naming convention and file list

- Use a **naming convention** where each file name starts with a number, reflecting the order of use in the presentation of the tutorial.
- List your slide files in a markdown, with a brief description.


+++ {"slideshow": {"slide_type": "slide"}} 
-->


**Details** <br />
Learn about the Model Asset Exchange (MAX) where you can deploy your model locally as a Microservice on Docker, or IBM Cloud.


🎓 What will you learn? <br />
- What is the Model Asset Exchange (MAX)
- How can you deploy a Deep Learning model.
- How does the model get deployed and trained over a Container.
- We'll conclude with an interactive lab where we will deploy a model from MAX.

👩‍💻 Who should attend? <br />
Developers and those interested in OpenShift, and IBM Watson Discovery.

+++ {"slideshow": {"slide_type": "subslide"}}

🎙️ Speakers
- Mridul Bhandari, IBM Developer Advocate, U.A.E - (https://lnkd.in/drsgBWn)
- Mostafa Abdelaleem, IBM Developer Advocate, Egypt -
(https://lnkd.in/dHBq67m)

🎈 Prerequisites <br />
1) Sign up to IBM Cloud using this link: https://ibm.biz/MAXDeepLearning <br />
2) Register for the live event or watch the recording: https://www.crowdcast.io/e/maxdeeplearning

👩‍💻Resources 
- GitHub Repository - https://ibm.biz/MAXTutorial
- Workshop Slides - https://ibm.biz/MAXResources
- Survey - https://ibm.biz/MAXSurvey
- Meetup page - https://www.meetup.com/IBM-Cloud-MEA/events/ 

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide1.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide2.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide3.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide4.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide5.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide6.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide7.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide8.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide9.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide10.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide11.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide12.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide13.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide14.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide15.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide16.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide17.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide18.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide19.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide20.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide21.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

![center](https://github.com/mridulrb/Deep-Learning-on-Model-Asset-Exchange/blob/master/images/slide_images/Slide22.jpeg?raw=true)

+++ {"slideshow": {"slide_type": "slide"}}

## License

**Recommend** that slides be shared under a [CC-BY](https://creativecommons.org/licenses/by/4.0/) license.
