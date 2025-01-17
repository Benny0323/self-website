---
title: "RTUNet++: Assessment of Osteosarcoma MRI Image Segmentation leveraging Hybrid CNN-Transformer Approach with Dense Skip Connection"
authors:
- Binfeng Zou
- Yifei Chen
- admin
- Yifei Sun
- Yifan Huang
- Feiwei Qin
- Changmiao Wang

date: "2023-10-09T00:00:00Z"
doi: "10.1109/ICSIP57908.2023.10270849"


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: In *ICSIP 2023*
publication_short: In *ICSIP 2023*

abstract: Orthopedic osteosarcoma is a prevalent malignant bone tumor. Preoperative planning, efficacy evaluation, and metastasis detection of osteosarcoma necessitate the use of magnetic resonance imaging (MRI). Due to the varying 10-cations, structures, sizes, and shapes of osteosarcomas among patients, as well as the high degree of tumor heterogeneity, segmenting osteosarcoma images manually presents a significant challenge for clinicians. In the meantime, the grayscale and texture features within the tumor in MRI images are not homogeneous, resulting in small grayscale differences between the tumor tissue and the surrounding normal tissue, which also presents a significant challenge for deep learning-based image segmentation methods. This paper proposes RTUNet++, a novel method for segmenting osteosarcoma MRI images. This method integrates the ResNet residual module, Transformer attention mechanism, and UNet++ Dense Skip Connection structure. We employ a CNN-Transformer hybrid architecture to prevent the loss of spatial feature data. Features with different semantic scales are aggregated at the decoder using multi-fusion dense jump connections to achieve flexible feature fusion. Consequently, in comparison experiments with various classical models, our proposed RTUNet++ achieves superior segmentation results on an osteosarcoma MRI image dataset.

# Summary. An optional shortened abstract.
summary: We propose RTUNet++, which integrates ResNet residuals, Transformer attention, and UNet++ dense skip connections for enhanced feature fusion. RTUNet++ outperforms classical models on osteosarcoma MRI datasets, demonstrating superior segmentation performance.

tags: []
featured: false

url_pdf: https://ieeexplore.ieee.org/abstract/document/10270849

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
