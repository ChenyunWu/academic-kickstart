---
title: "Reasoning about Fine-grained Attribute Phrases using Reference Games"
authors:
- Jong-Chyi Su*
- Chenyun Wu*
- Huaizu Jiang
- Subhransu Maji
date: "2017-10-22"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-10-22"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

external_link: https://people.cs.umass.edu/~jcsu/papers/visdiff/

# Publication name and optional abbreviated publication name.
publication: International Conference on Computer Vision 2017
publication_short: ICCV 2017

abstract: We present a framework for learning to describe fine-grained visual differences between instances using attribute phrases. Attribute phrases capture distinguishing aspects of an object (e.g., "propeller on the nose" or "door near the wing" for airplanes) in a compositional manner. Instances within a category can be described by a set of these phrases and collectively they span the space of semantic attributes for a category. We collect a large dataset of such phrases by asking annotators to describe several visual differences between a pair of instances within a category. We then learn to describe and ground these phrases to images in the context of a reference game between a speaker and a listener. The goal of a speaker is to describe attributes of an image that allows the listener to correctly identify it within a pair. Data collected in a pairwise manner improves the ability of the speaker to generate, and the ability of the listener to interpret visual descriptions. Moreover, due to the compositionality of attribute phrases, the trained listeners can interpret descriptions not seen during training for image retrieval, and the speakers can generate attribute-based explanations for differences between previously unseen categories. We also show that embedding an image into the semantic space of attribute phrases derived from listeners offers 20% improvement in accuracy over existing attribute-based representations on the FGVC-aircraft dataset.


# Summary. An optional shortened abstract.
summary: ICCV 2017<br>We use attribute phrases to describe fine-grained visual differences between instances. We collect a large dataset, design a listener and a speaker to play the reference game, and apply the trained models to fine-grained classification as well as telling the difference between categories.
tags:
featured: true

links:
- name: Code and Data
  url: 'https://github.com/jongchyisu/attribute_phrases'
url_pdf: 'https://arxiv.org/abs/1708.08874'
url_poster: 'http://supermoe.cs.umass.edu/visdiff/poster.pdf'
url_slides: 'http://supermoe.cs.umass.edu/visdiff/slides.pdf'

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
- [Jong-Chyi Su*](https://people.cs.umass.edu/~jcsu/)
- [Chenyun Wu*](https://people.cs.umass.edu/~chenyun)
- [Huaizu Jiang](http://jianghz.me/)
- [Subhransu Maji](http://people.cs.umass.edu/~smaji/)
