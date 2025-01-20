---
title: Weakly Supervised Segmentation of Hyper-Reflective Foci with Compact Convolutional Transformers and SAM2
authors:
- admin
- Justus Bisten
- Maximilian W. M. Wintergerst
- Robert P. Finger
- Thomas Schultz
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2025-01-10'
doi: '
https://doi.org/10.48550/arXiv.2501.05933'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-01-10T00:00:00.0Z'
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article']

# Publication name and optional abbreviated publication name.
publication: In *Arxiv*
#publication_short: In *DAGM GCPR*

abstract: Weakly supervised segmentation has the potential to greatly reduce the annotation effort for training segmentation models for small structures such as hyper-reflective foci (HRF) in optical coherence tomography (OCT). However, most weakly supervised methods either involve a strong downsampling of input images, or only achieve localization at a coarse resolution, both of which are unsatisfactory for small structures. We propose a novel framework that increases the spatial resolution of a traditional attention-based Multiple Instance Learning (MIL) approach by using Layer-wise Relevance Propagation (LRP) to prompt the Segment Anything Model (SAM~2), and increases recall with iterative inference. Moreover, we demonstrate that replacing MIL with a Compact Convolutional Transformer (CCT), which adds a positional encoding, and permits an exchange of information between different regions of the OCT image, leads to a further and substantial increase in segmentation accuracy.

# Summary. An optional shortened abstract.
#summary: 


tags: ['Optical Coherence Tomography', 'HRF', 'Segmentaiton', 'SAM2']

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2501.05933'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, place an image named `featured.jpg/png` in your page's folder.
# Otherwise, specify the `filename` option to load an image from your `assets/media/` folder.
# Placement options: 1 = Full column width, 2 = Out-set, 3 = Screen-width
# Focal point options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
# Set `preview_only` to `true` to just use the image for thumbnails.
image:
  caption: ''
  placement: 2
  focal_point: 'Top'
  preview_only: true
  # filename: my-image.jpg  # Uncomment to load an image from `assets/media/` instead.
  #alt_text: An optional description of the image for screen readers.
  

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example

# The following can be added to the main body (optional)
#{{% callout note %}}
#Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
#{{% /callout %}}

#{{% callout note %}}
#Create your slides in Markdown - click the _Slides_ button to check out the example.
#{{% /callout %}}

#Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.#hugoblox.com/content/writing-markdown-latex/).
---