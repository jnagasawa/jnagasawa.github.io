---
title: "Emotion Classification from Gaze Data Alone: A Deep Learning Approach without Pupil Diameter"
authors:
  - ["Junichi Nagasawa", "Mamoru Hiroe", "Yuichi Nakata", "Yuji Maegawa, Junzo Kamahara, Naoki Hojo, Tetsuya Takiguchi, Saizo Aoyagi, Michiya Yamamoto, Takashi Nagamatsu"]
# - admin
# date: "2024-12-07T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-10-21T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: There is active research on estimating emotions by analyzing facial expressions and pupil responses using facial images. Due to fake facial expressions or changes in environmental brightness, it may not be possible to estimate emotions from facial expressions or pupil diameter. Therefore, we propose a method to estimate emotions from gaze alone. This study proposes a method to classify emotions by fine-tuning gazeNet, a gaze classification model into fixation, saccade, etc. to compensate for the lack of data for deep learning. We evaluated the proposed methods in three ways, classifying emotions into four categories (delighted, relaxed, bored, and afraid), two categories (negative and positive valence), and two categories (low and high arousal), which are based on Russell’s circumplex model. The result of the four-category classification shows that emotions associated with higher arousal, i.e., delighted and afraid, exhibited higher accuracy. Classification along the valence axis suggests that valence classification using gaze data alone is difficult. Classification along the arousal axis suggests that high-arousal states achieve higher recall, precision, and F-measure compared to low-arousal states. In this study, we showed that emotion classification from gaze alone using transfer learning with a pre-trained model that classifies gaze was effective on the arousal axis.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:

featured: true

# links:
# - name: Custom Link
#   url: http://example.org
# url_pdf: http://arxiv.org/pdf/1512.04133v1
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
<!-- 
{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
