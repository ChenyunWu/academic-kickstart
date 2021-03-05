+++
# Experience widget.
widget = "experience"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.

title = "Working Experience"
subtitle = ""

# Date format for experience
#   Refer to https://sourcethemes.com/academic/docs/customization/#date-format
date_format = "Jan 2006"

# Experiences.
#   Add/remove as many `[[experience]]` blocks below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin/end multi-line descriptions with 3 quotes `"""`.
[[experience]]
  title = "Computer Vision Research Intern"
  company = "ByteDance"
  company_url = "https://www.bytedance.com/en/"
  location = "Mountain View, CA, US" 
  date_start = "2020-06-01"
  date_end = "2020-09-04"
  description = """
I worked with Xiaohui Shen, Xiaojie Jin, and Longyin Wen on localizing clips in videos with natural language descriptions.
- Reproduced and visualized results from state-of-the-art models (DRN, LGI, CMINS). Analyzed and compared datasets (ActivityNet-Captions, Charades-STA, TACoS).
- Implemented a graph convolutional net to reason the target clip with language syntactics.
- Designed an attention mechanism to leverage object detection results to associate frames with nouns in sentences.
"""

[[experience]]
  title = "Computer Vision Research Intern"
  company = "Adobe"
  company_url = "https://www.adobe.com/"
  location = "San Jose, CA, US"
  date_start = "2018-05-01"
  date_end = "2019-03-01"
  description = """
I worked with Zhe Lin, Scott Cohen, and Trung Bui on large-scale visual grounding. Our work was published on CVPR 2020 as "PhraseCut: Language-based Image Segmentation in the Wild".
  """
  
[[experience]]
  title = "Software Engineering Intern"
  company = "Google"
  company_url = "https://www.google.com/"
  location = "Mountain View, CA, US"
  date_start = "2017-06-01"
  date_end = "2017-09-01"
  description = """
I worked with Nick Johnston, George Toderici, David Minnen, and Michele Covell on deep image compression.
- Implemented a U-Net image compression model with quantizers and binarizers on skip connections at different levels. 
- Designed and tuned the training procedure to analyze the effectiveness of each skip connection.
- Enabled different trade-offs between compression size and quality by turning on and off some skip connections.
  """

+++
