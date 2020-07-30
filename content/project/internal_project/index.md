---
title: Colorectal cancer tumoroid project
summary: This project utilised DNA-exome sequencing on colorectal tumoroid and normal organoid grown in 3D culture and were analysed for somatic mutations in order to indentify patient specific drug targets. Here we show some of the analyses run as part of our Exome and somatic variant discovery pipeline.
tags:
- Somatic Variants
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart

links:
- icon: twitter
  icon_pack: fab
  name: Follow
  url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: example
---

## Introduction

Our collaborator Dr Mark Williams provided us with high quality DNA-exome sequence from 3D culture tumoroid and organoid cultures to be processed by our somatic variant discovery pipeline. This page will describe some of the analyses performed for this project....


## Methods

The samples are first passed through our rigorous quality control (QC) pipeline (see QC section) to ensure that samples are of high quality and to remove sequencing and amplification artefacts and were mapped using the Wellcome Trust and DKFZ to align sequence reads (cgpMAP; https://github.com/cancerit/dockstore-cgpmap). 

For variant calling, 2 independent somatic variant discovery pipelines were run on samples, our 'GATK mutect2 workflow' and 'cgpWXS' (Sanger exome pipeline - utilising CaVEMan and Pindel software; https://github.com/cancerit/dockstore-cgpwxs) pipelines.   







