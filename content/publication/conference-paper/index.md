---
title: 'UWAT-GAN: Fundus Fluorescein Angiography Synthesis via Ultra-wide-angle Transformation Multi-scale GAN'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Zhaojie Fang
  - admin
  - Pengxue Wei
  - Wangting Li
  - Shaochong Zhang
  - Ahmed Elazab
  - Gangyong Jia
  - Ruiquan Ge
  - Changmiao Wang

date: '2023-10-01T00:00:00Z'
doi: 'https://doi.org/10.1007/978-3-031-43990-2_70'
appendix: 'https://drive.google.com/file/d/121e5AR0qzqzKpdttEEUZZzWPi5fI7_kz/view?usp=sharing'


# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *MICCAI 2023 **(Early Accept)***
publication_short: In *MICCAI 2023 **(Early Accept)***

Abstract: Fundus photography is an essential examination for clinical and differential diagnosis of fundus diseases. Recently, Ultra-Wide-angle Fundus (UWF) techniques, UWF Fluorescein Angiography (UWF-FA), and UWF Scanning Laser Ophthalmoscopy (UWF-SLO) have been gradually put into use. However, Fluorescein Angiography (FA) and UWF-FA require injecting sodium fluorescein which may have detrimental influences. To avoid negative impacts, cross-modality medical image generation algorithms have been proposed. Nevertheless, current methods in fundus imaging cannot produce high-resolution images and are unable to capture tiny vascular lesion areas. This paper proposes a novel conditional generative adversarial network (UWAT-GAN) to synthesize UWF-FA from UWF-SLO. Using multi-scale generators and a fusion module patch to better extract global and local information, our model can generate high-resolution images. Moreover, an attention transmit module is proposed to help the decoder learn effectively. Besides, a supervised approach is used to train the network using multiple new weighted losses on different scales of data. Experiments on an in-house UWF image dataset demonstrate the superiority of the UWAT-GAN over the state-of-the-art methods.

# Summary. An optional shortened abstract.
summary: Our method can be used to turn UWF scanning laser ophthalmoscopy(UWF-SLO) to UWF fluorescein angiography(UWF-FFA) and display the tiny vascular lesion areas.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2307.11530'
url_code: 'https://github.com/Tinysqua/UWAT-GAN'
url_poster: 'https://drive.google.com/file/d/1Yq8IqlpCkR1D3OT4esP_XjrdROfmJ-DU/view?usp=sharing'
url_video: 'https://drive.google.com/file/d/1wjcBl1o1jraU4p8dODYVbjYO_Fwehf4o/view?usp=sharing'
url_slides: 'https://docs.google.com/presentation/d/1Cx6SfoetjgjTh7Kr15fNEFZw6UOCDsl8/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true'
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
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



title: 'RTUNet++: Assessment of Osteosarcoma MRI Image Segmentation leveraging Hybrid CNN-Transformer Approach with Dense Skip Connection'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Binfeng Zou
  - Yifei Chen
  - admin
  - Yifei Sun
  - Yifan Huang
  - Feiwei Qin
  - Changmiao Wang

date: '2023-10-01T00:00:00Z'
doi: 'https://doi.org/10.1109/ICSIP57908.2023.10270849'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *2023 8th International Conference on Signal and Image Processing (ICSIP)*
publication_short: In *ICSIP 2023*

Abstract: Orthopedic osteosarcoma is a prevalent malignant bone tumor. Preoperative planning, efficacy evaluation, and metastasis detection of osteosarcoma necessitate the use of magnetic resonance imaging (MRI). Due to the varying 10-cations, structures, sizes, and shapes of osteosarcomas among patients, as well as the high degree of tumor heterogeneity, segmenting osteosarcoma images manually presents a significant challenge for clinicians. In the meantime, the grayscale and texture features within the tumor in MRI images are not homogeneous, resulting in small grayscale differences between the tumor tissue and the surrounding normal tissue, which also presents a significant challenge for deep learning-based image segmentation methods. This paper proposes RTUNet++, a novel method for segmenting osteosarcoma MRI images. This method integrates the ResNet residual module, Transformer attention mechanism, and UNet++ Dense Skip Connection structure. We employ a CNN-Transformer hybrid architecture to prevent the loss of spatial feature data. Features with different semantic scales are aggregated at the decoder using multi-fusion dense jump connections to achieve flexible feature fusion. Consequently, in comparison experiments with various classical models, our proposed RTUNet++ achieves superior segmentation results on an osteosarcoma MRI image dataset.

# Summary. An optional shortened abstract.
summary: This paper proposes RTUNet++, a novel hybrid CNN-Transformer model for segmenting osteosarcoma MRI images, integrating ResNet, Transformer attention, and UNet++ dense skip connections to address tumor heterogeneity and grayscale challenges, achieving superior performance compared to classical models.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://arxiv.org/pdf/2307.11530'
url_code: 'https://github.com/Tinysqua/UWAT-GAN'
url_poster: 'https://drive.google.com/file/d/1Yq8IqlpCkR1D3OT4esP_XjrdROfmJ-DU/view?usp=sharing'
url_video: 'https://drive.google.com/file/d/1wjcBl1o1jraU4p8dODYVbjYO_Fwehf4o/view?usp=sharing'
url_slides: 'https://docs.google.com/presentation/d/1Cx6SfoetjgjTh7Kr15fNEFZw6UOCDsl8/edit?usp=sharing&ouid=107677953599522928486&rtpof=true&sd=true'
# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  focal_point: ''
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

