---
title: "Attempts on detecting Alzheimer's disease by fine-tuning pre-trained model with Gaze Data"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-04-01T00:00:00Z'
doi: 'https://doi.org/10.1145/3649902.3656360'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *ACM ETRA 2024 COGAIN*
publication_short: In *ACM ETRA 2024 COGAIN*

abstract: Early detection of Alzheimer’s disease (AD) is important but difficult. Screening for AD using neuropsychological tests such as mini-mental state examination (MMSE) is time-consuming and burdensome for patients. Recently, several methods have been reported for detecting AD based on eye movements. However, analyzing eye movements requires considerable effort. Although machine learning from eye movement data is a strong candidate for labor-saving, it requires large datasets. In this study, we modify an existing pre-trained deep neural network model, gazeNet, for transfer learning. For evaluation, we exclusively used data from one participant and fine-tuned the model using data from all the remaining participants. We repeated this procedure separately for each of the 14 participants. The results of eye movement during the antisaccade task were not satisfactory for the discrimination of AD, and detailed analysis suggested that the data might potentially have a correlation with MMSE scores in the mild cognitive impairment range.

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: 'https://doi.org/10.1145/3649902.3656360'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}} -->

<!-- {{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}} -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
