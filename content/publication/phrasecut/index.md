---
title: "PhraseCut: Language-based Image Segmentation in the Wild"
authors:
- admin
- Zhe Lin
- Scott Cohen
- Trung Bui
- Subhransu Maji
date: "2020-06-16"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-06-16"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: Conference on Computer Vision and Pattern Recognition 2020
publication_short: CVPR 2020

abstract: We consider the problem of segmenting image regions given a natural language phrase, and study it on a novel dataset of 77,262 images and 345,486 phrase-region pairs. Our dataset is collected on top of the Visual Genome dataset and uses the existing annotations to generate a challenging set of referring phrases for which the corresponding regions are manually annotated. Phrases in our dataset correspond to multiple regions and describe a large number of object and stuff categories as well as their attributes such as color, shape, parts, and relationships with other entities in the image. Our experiments show that the scale and diversity of concepts in our dataset poses significant challenges to the existing state-of-the-art. We systematically handle the long-tail nature of these concepts and present a modular approach to combine category, attribute, and relationship cues that outperforms existing approaches.

# Summary. An optional shortened abstract.
summary: CVPR 2020<br>We consider the problem of segmenting image regions given a natural language phrase. We propose a larger-scale dataset that covers more concepts and allows more flexible target regions. Our modular method enables uniform treatment of things and stuff and improves performance on rare categories.

tags:
featured: true

links:
- name: Code and Data
  url: 'https://github.com/ChenyunWu/PhraseCutDataset'
url_pdf: 'https://arxiv.org/abs/2008.01187'
# url_poster: 'https://people.cs.umass.edu/~chenyun/phrasecut/docs/NECV2019/NECV2019_poster_PhraseCut.pdf'
url_slides: 'https://drive.google.com/file/d/1-orLmWJs93jeplA496P97ecoRQ2HpArU/view'
url_video: '/phrasecut/phrasecut-1min.mp4'

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
- [Zhe Lin](https://research.adobe.com/person/zhe-lin/)
- [Scott Cohen](https://research.adobe.com/person/scott-cohen/)
- [Trung Bui](https://research.adobe.com/person/trung-bui/)
- [Subhransu Maji](http://people.cs.umass.edu/~smaji/)

### **Presentation**
<video width="100%" controls>
  <source src="/~chenyun/media/phrasecut-1min.mp4" type="video/mp4"> </source>
</video>

### **Dataset**
We introduce VGPhraseCut Dataset, which is aimed for segmenting anything on an image based on a regional description phrase. The dataset is collected based on Visual Genome. It contains 345,486 phrase-region pairs. Each phrase contains explicit annotations of which words describe the category name, attributes, and relationships with other things in the image respectively. The corresponding region described by the phrase is a binary segmentation mask on the image. Dataset and API code can be downloaded [here](https://github.com/ChenyunWu/PhraseCutDataset). Below are a few examples.

![example](/~chenyun/media/phrasecut_data.jpg)