---
title: 'kNN For Whisper And Its Effect On Bias And Speaker Adaptation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  # - Maya K. Nachesa
  - Vlad Niculae

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2025-05-01'

# Schedule page publish date (NOT publication's date).
# publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *NAACL*
publication_short: In *NAACL*

abstract: Speech recognition performance varies by language, domain, and speaker characteristics such as accent, but fine-tuning a model on any of these categories may lead to catastrophic forgetting. Token-level k nearest neighbor search (kNN), first proposed for neural sequence decoders for natural language generation (NLG) and machine translation (MT), is a non-parametric method that instead adapts using inference-time search in an external datastore, without training the underlying model. We show that Whisper, a transformer end-to-end speech model, benefits from kNN. We investigate the differences between the speech and text setups. We discuss implications for speaker adaptation, and analyze improvements by gender, accent, and age.

# # Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - kNN
  - ASR

# Display this page in the Featured widget?
featured: true

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.18653/v1/2025.findings-naacl.369

# Custom links
# links:
#   - type: pdf
#     url: ""
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
