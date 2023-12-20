---
title: Accurate drusen segmentation in optical coherence tomography via order-constrained
  regression of retinal layer heights
authors:
- admin
- Maximilian WM Wintergerst
- Robert P Finger
- Thomas Schultz
# Author notes (optional)
#author_notes:
#  - 'Equal contribution'
#  - 'Equal contribution'

date: '2023-05-19'
doi: 'https://doi.org/10.1038/s41598-023-35230-4'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-12-20T14:02:48.467030Z'
# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['article-journal']

# Publication name and optional abbreviated publication name.
publication: In *Scientific Reports*
publication_short: In *Sci. Rep.*

abstract: Drusen are an important biomarker for age-related macular degeneration (AMD). Their accurate segmentation based on optical coherence tomography (OCT) is therefore relevant to the detection, staging, and treatment of disease. Since manual OCT segmentation is resource-consuming and has low reproducibility, automatic techniques are required. In this work, we introduce a novel deep learning based architecture that directly predicts the position of layers in OCT and guarantees their correct order, achieving state-of-the-art results for retinal layer segmentation. In particular, the average absolute distance between our model’s prediction and the ground truth layer segmentation in an AMD dataset is 0.63, 0.85, and 0.44 pixel for Bruch's membrane (BM), retinal pigment epithelium (RPE) and ellipsoid zone (EZ), respectively. Based on layer positions, we further quantify drusen load with excellent accuracy, achieving 0.994 and 0.988 Pearson correlation between drusen volumes estimated by our method and two human readers, and increasing the Dice score to 0.71 ± 0.16 (from 0.60 ± 0.23) and 0.62 ± 0.23 (from 0.53 ± 0.25), respectively, compared to a previous state-of-the-art method. Given its reproducible, accurate, and scalable results, our method can be used for the large-scale analysis of OCT data.

# Summary. An optional shortened abstract.
summary: A novel deep learning based architecture that directly predicts the position of layers in OCT and guarantees their correct order is introduced, achieving state-of-the-art results for retinal layer segmentation.


tags: ['Medicine', 'Engineering', 'Computer Science']

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://www.nature.com/articles/s41598-023-35230-4.pdf'
url_code: 'https://github.com/MedVisBonn/eyeseg'
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
  caption: 'Image credit: [**nature.com**](https://www.nature.com/articles/s41598-023-35230-4/figures/1)'
  placement: 1
  focal_point: 'Smart'
  preview_only: false
  # filename: my-image.jpg  # Uncomment to load an image from `assets/media/` instead.
  #alt_text: An optional description of the image for screen readers.
  

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - eyeseg
  - eyepy

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


