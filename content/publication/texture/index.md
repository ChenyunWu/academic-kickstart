---
title: "Describing Textures using Natural Language"
authors:
- admin
- Mikayla Timm
- Subhransu Maji
date: "2020-08-24"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-08-23"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: European Conference on Computer Vision 2020 Oral
publication_short: ECCV 2020

abstract: Textures in natural images can be characterized by color, shape, periodicity of elements within them, and other attributes that can be described using natural language. In this paper, we study the problem of describing visual attributes of texture on a novel dataset containing rich descriptions of textures, and conduct a systematic study of current generative and discriminative models for grounding language to images on this dataset. We find that while these models capture some properties of texture, they fail to capture several compositional properties, such as the colors of dots. We provide critical analysis of existing models by generating synthetic but realistic textures with different descriptions. Our dataset also allows us to train interpretable models and generate language-based explanations of what discriminative features are learned by deep networks for fine-grained categorization where texture plays a key role. We present visualizations of several fine-grained domains and show that texture attributes learned on our dataset offer improvements over expert-designed attributes on the Caltech-UCSD Birds dataset.


# Summary. An optional shortened abstract.
summary: ECCV 2020 Oral<br>A novel dataset of textures with natural language descriptions and analysis of several language and vision models.

tags:
featured: true

links:
- name: Code and Data
  url: 'https://github.com/ChenyunWu/DescribingTextures'
url_pdf: 'https://arxiv.org/abs/2008.01180'
# url_poster: 'https://people.cs.umass.edu/~chenyun/phrasecut/docs/NECV2019/NECV2019_poster_PhraseCut.pdf'
# url_slides: 'https://drive.google.com/file/d/1-orLmWJs93jeplA496P97ecoRQ2HpArU/view'
url_video: 'https://drive.google.com/file/d/1VjtH18EWsZmYvOK1y8oNYu5nPSGDj33h/view?usp=sharing'


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

---
### **Authors**
- [Chenyun Wu](https://people.cs.umass.edu/~chenyun)
- [Mikayla Timm](https://mtimm100.github.io/)
- [Subhransu Maji](http://people.cs.umass.edu/~smaji/)

### **Presentation**
<video width="100%" controls>
  <source src="/media/Texture-2min.mp4" type="video/mp4"> </source>
</video>

A 10-min presentation is available [here](https://drive.google.com/file/d/1VjtH18EWsZmYvOK1y8oNYu5nPSGDj33h/view?usp=sharing).

### **Dataset**
We introduce our Describable Textures in Detail Dataset (DTD2), where descriptions are collected on texture images. In total there are 5369 images and 4.6 descriptions per image. It dramatically expands the vocabulary used to describe textures.
You can follow [this link](https://github.com/ChenyunWu/DescribingTextures) to download our code and dataset.
Below are a few examples.

![data_example](/media/texture_data.jpg)