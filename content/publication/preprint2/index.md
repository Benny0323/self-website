---
title: "BS-LDM: Effective Bone Suppression in
High-Resolution Chest X-Ray Images with
Conditional Latent Diffusion Models"
authors:
- Yifei Sun
- admin
- Hao Zheng
- Wenming Deng
- Jin Liu
- Wenwen Min
- Ahmed Elazab
- Xiang Wan
- Changmiao Wang
- Ruiquan Ge

date: "2024-12-30T00:00:00Z"
doi: "https://doi.org/10.48550/arXiv.2412.15670"


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: In *JBHI 2025 **Under Review***
publication_short: In *JBHI 2025 **Under Review***

abstract: Lung diseases represent a significant global health challenge, with Chest X-Ray (CXR) being a key diagnostic tool due to their accessibility and affordability. Nonetheless, the detection of pulmonary lesions is often hindered by overlapping bone structures in CXR images, leading to potential misdiagnoses. To address this issue, we developed an end-to-end framework called BS-LDM, designed to effectively suppress bone in high-resolution CXR images. This framework is based on conditional latent diffusion models and incorporates a multi-level hybrid loss-constrained vector-quantized generative adversarial network which is crafted for perceptual compression, ensuring the preservation of details. To further enhance the framework's performance, we introduce offset noise and a temporal adaptive thresholding strategy. These additions help minimize discrepancies in generating low-frequency information, thereby improving the clarity of the generated soft tissue images. Additionally, we have compiled a high-quality bone suppression dataset named SZCH-X-Rays. This dataset includes 818 pairs of high-resolution CXR and dual-energy subtraction soft tissue images collected from a partner hospital. Moreover, we processed 241 data pairs from the JSRT dataset into negative images, which are more commonly used in clinical practice. Our comprehensive experimental and clinical evaluations reveal that BS-LDM excels in bone suppression, underscoring its significant clinical value. Our code, pre-trained models and processed JSRT dataset are available at https://github.com/diaoquesang/BS-LDM.

# Summary. An optional shortened abstract.
summary: We propose an end-to-end framework BS-LDM for suppressing bones in high-resolution CXR images, improving soft tissue clarity with advanced diffusion models and hybrid loss strategies. Its clinical value is validated using the SZCH-X-Rays and processed JSRT datasets.

tags: []
featured: true

url_pdf: https://www.arxiv.org/pdf/2412.15670
url_code: 'https://github.com/diaoquesang/BS-LDM'

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
