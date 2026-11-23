---
title: 'You Have a Face for Radio: Bias in Multimodal Speech Recognition Models'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  # - Maya K. Nachesa
  - Vagrant Gautam
  - Vlad Niculae

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2026-10'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *EMNLP*
publication_short: In *EMNLP*

abstract: As large neural models have become better at language tasks, researchers are increasingly building multi- and omnimodal models that handle more than one modality of data. One example is the expansion of speech recognition models to audio-visual data, the goal being noise mitigation and multimodal subtitling. While performance and bias have been studied extensively in the single-modality regime, it is unknown how new modalities affect this, even though they produce biases in humans. We therefore propose the first bias evaluation of multimodal speech recognition, where we create videos pairing different faces with the same audio using lip-sync, and measure changes in speech transcription accuracy. We find large quality-of-service differences across mWhisper-Flamingo and Gemini models, with drops of up to 4.05 word error rate points, across self-declared gender, ethnicity, and their intersection. Our findings point to a priority for developers to evaluate, fix, and communicate such limitations, as providing more signals through additional modalities is not necessarily better, and may even lead to biased outcomes.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Audio-Visual Speech Transcription
  - Bias

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/2026.emnlp-main.2681

# Custom links
links:
  - type: pdf
    url: ""
  # - type: code
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: dataset
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: slides
  #   url: https://www.slideshare.net/
  # - type: source
  #   url: https://github.com/HugoBlox/hugo-blox-builder
  # - type: video
  #   url: https://youtube.com

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
#   - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: ""
---

<!-- > [!NOTE]
> Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.

> [!NOTE]
> Create your slides in Markdown - click the _Slides_ button to check out the example. -->

<!-- Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
