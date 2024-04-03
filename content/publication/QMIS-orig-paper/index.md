---
title: "Hemodynamic property incorporated brain tumor segmentation by deep learning and density-based analysis of dynamic susceptibility contrast-enhanced magnetic resonance imaging (MRI)"
authors:
- Leonardo Tang
- Tianhe (Rory) Wu
- Ranliang Hu
- Quanquan Gu
- Xiaofeng Yang
- Hui Mao

author_notes: ''
date: "2024-04-03T00:00:00Z"
doi: "https://doi.org/10.21037/qims-23-1471"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-04-12T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Quantitative Imaging in Medicine & Surgery"
publication_short: ""

abstract: "Background: Magnetic resonance imaging (MRI) is a primary non-invasive imaging modality for tumor
segmentation, leveraging its exceptional soft tissue contrast and high resolution. Current segmentation
methods typically focus on structural MRI, such as T1-weighted post-contrast-enhanced or fluid-attenuated
inversion recovery (FLAIR) sequences. However, these methods overlook the blood perfusion and
hemodynamic properties of tumors, readily derived from dynamic susceptibility contrast (DSC) enhanced
MRI. This study introduces a novel hybrid method combining density-based analysis of hemodynamic
properties in time-dependent perfusion imaging with deep learning spatial segmentation techniques to
enhance tumor segmentation.
Methods: First, a U-Net convolutional neural network (CNN) is employed on structural images to
delineate a region of interest (ROI). Subsequently, Hierarchical Density-Based Scans (HDBScan) are
employed within the ROI to augment segmentation by exploring intratumoral hemodynamic heterogeneity
through the investigation of tumor time course profiles unveiled in DSC MRI.
Results: The approach was tested and evaluated using a cohort of 513 patients from the open-source
University of Pennsylvania glioblastoma database (UPENN-GBM) dataset, achieving a 74.83% Intersection
over Union (IoU) score when compared to structural-only segmentation. The algorithm also exhibited
increased precision and localized predictions of heightened segmentation boundary complexity, resulting
in a 146.92% increase in contour complexity (ICC) compared to the reference standard provided by the
UPENN-GBM dataset. Importantly, segmenting tumors with the developed new approach uncovered
a negative correlation of the tumor volume with the scores in the Karnofsky Performance Scale (KPS)
clinically used for assessing the functional status of patients (−0.309), which is not observed with the
prevailing segmentation standard.
Conclusions: This work demonstrated that including hemodynamic properties of tissues from DSC
MRI can improve existing structural or morphological feature-based tumor segmentation techniques with
additional information on tumor biology and physiology. This approach can also be applied to other clinical
indications that use perfusion MRI for diagnosis or treatment monitoring.
Keywords: Brain tumor; segmentation; dynamic susceptibility contrast (DSC); perfusion magnetic resonance
imaging (perfusion MRI); deep learning"

# Summary. An optional shortened abstract.
summary: In this paper, we presents a novel hybrid method that improves brain tumor segmentation by integrating hemodynamic properties from dynamic susceptibility contrast (DSC) enhanced MRI with deep learning spatial segmentation techniques. The approach, tested on a cohort of 513 patients, demonstrated enhanced segmentation precision and the ability to uncover hemodynamic heterogeneity within tumors, showing potential for more accurate tumor monitoring and treatment response assessment.. 

tags:
- Source Themes
featured: true

# links:
# - name: ""
# url: 
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
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""


---
<!-- 
{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
