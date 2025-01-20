---
title: Foundation Models Permit Retinal Layer Segmentation Across OCT Devices
authors:
- admin
- Thomas Schultz
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2024-09-10'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2024-09-26T00:00:00.0Z'
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *DAGM German Conference on Pattern Recognition*
publication_short: In *DAGM GCPR*

abstract: The segmentation of retinal layers in images from optical coherence tomography (OCT) is an important step in ophthalmological diagnosis and disease monitoring. Current CNN-based models perform well on images from the same OCT scanner on which they have been trained, but their performance can degrade drastically when images are acquired with other devices. We present the first method for OCT layer segmentation that builds on recent Vision Transformer (ViT) foundation models. We demonstrate that, compared to a state-of-the-art CNN approach, doing so significantly improves their ability to generalize to devices for which no training data was available. This highlights the potential of foundation models to enable more robust medical image analysis. We also analyze the effect of using different foundation models. Notably, more generic foundation models from computer vision permitted better generalization than an equally large foundation model that was specifically trained for OCT analysis.

# Summary. An optional shortened abstract.
summary: Segmenting retinal layers in OCT images is crucial for ophthalmological diagnosis, but current CNN models struggle with images from different devices. We introduce the first OCT layer segmentation method using Vision Transformer (ViT) foundation models, which significantly improve generalization to unseen devices and demonstrate that generic foundation models outperform equally large OCT-specific models in robustness.


tags: ['Optical Coherence Tomography', 'Foundation Models', 'Retinal Layer Segmentation']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'morelle-2024-foundation.pdf'
url_code: ''
url_dataset: ''
url_poster: 'Morelle2024_Poster_GCPR_FoundationModelsForLayerSegmentation.pdf'
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


