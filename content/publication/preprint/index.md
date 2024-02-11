---
title: "BS-Diff: Effective Bone Suppression Using Conditional Diffusion Models from Chest X-Ray Images"
authors:
- admin
- Yifei Sun
- Wenjian Qin
- Ruiquan Ge
- Cheng Pan
- Wenming Deng
- Zhou Liu
- Wenwen Min
- Ahmed Elazab
- Xiang Wan
- Changmiao Wang

date: "2023-11-26T00:00:00Z"
doi: ""


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *ISBI 2024*
publication_short: In *ISBI 2024*

abstract: Chest X-rays (CXRs) are commonly utilized as a low-dose modality for lung screening. Nonetheless, the efficacy of CXRs is somewhat impeded, given that approximately 75% of the lung area overlaps with bone, which in turn hampers the detection and diagnosis of diseases. As a remedial measure, bone suppression techniques have been introduced. The current dual-energy subtraction imaging technique in the clinic requires costly equipment and subjects being exposed to high radiation. To circumvent these issues, deep learning-based image generation algorithms have been proposed. However, existing methods fall short in terms of producing high-quality images and capturing texture details, particularly with pulmonary vessels. To address these issues, this paper proposes a new bone suppression framework, termed BS-Diff, that comprises a conditional diffusion model equipped with a U-Net architecture and a simple enhancement module to incorporate an autoencoder. Our proposed network cannot only generate soft tissue images with a high bone suppression rate but also possesses the capability to capture fine image details. Additionally, we compiled the largest dataset since 2010, including data from 120 patients with high-definition, high-resolution paired CXRs and soft tissue images collected by our affiliated hospital. Extensive experiments, comparative analyses, ablation studies, and clinical evaluations indicate that the proposed BS-Diff outperforms several bone-suppression models across multiple metrics.

# Summary. An optional shortened abstract.
summary: We propose a new bone suppression framework called BS-Diff, which utilizes a conditional diffusion model and a U-Net architecture to generate high-quality soft tissue images with high bone suppression rates.

tags: []
featured: false

url_pdf: https://arxiv.org/pdf/2311.15328.pdf
url_code: 'https://github.com/Benny0323/BS-Diff'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
---
