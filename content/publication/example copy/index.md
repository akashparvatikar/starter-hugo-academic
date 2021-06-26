---
title: "Prototypical models for classifying high-risk atypical breast lesions"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Om Choudhary
- Arvind Ramanathan
- Rebekah Jenkins
- Olga Navolotskaia
- Gloria Carter
- Akif Burak Tosun
- Jeffrey L. Fine
- S. Chakra Chennubhotla

# Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2021-09-29T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2021-09-29T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *International Conference on Medical Image Computing and Computer-Assisted Intervention (MICCAI)*
publication_short: In *MICCAI*

#abstract: Our goal in this paper is to build parametric models for a dictionary of histological patterns that aid in the differential diagnosis of atypical breast lesions and evaluate the inferential power of these hand-crafted features. Diagnosis of high-risk atypical breast lesions is challenging and remains a critical component of breast cancer screening, presenting even for experienced pathologists a more difficult classification problem than the binary detection task of cancer vs not-cancer. Following guidelines in the WHO classification of the tumors of the breast (an essential reference for pathologists, clinicians and researchers) and in consultation with our team of breast sub-specialists (N = 3), we assembled a visual dictionary of sixteen histological patterns (e.g., cribriform, picket-fence), a subset that pathologists frequently use in making complex diagnostic decisions of atypical breast lesions. We invoke parametric models for each pattern using a mix of unary, binary and ternary features that account for morphological and architectural tissue properties. We use 1441 ductal regions of interest (ROIs) extracted automatically from 93 whole slide images (WSIs) with a computational pathology pipeline. We collected diagnostic labels for all of the ROIs - normal and columnar cell changes (CCC) as low-risk benign lesions (= 1124), and flat epithelium atypia (FEA) and atypical ductal hyperplasia (ADH) as high-risk benign lesions (= 317). We generate likelihood maps for each dictionary pattern across a given ROI and integrate this information to determine a diagnostic label of high- or low-risk. Our method has comparable classification accuracies to the pool of breast pathology sub-specialists. Our study enables a deeper understanding of the discordance among pathologists in diagnosing atypical breast lesions.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags: []

# Display this page in the Featured widget?
featured: false

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: Springer Publisher'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---