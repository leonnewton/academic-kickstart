---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Context-rich Privacy Leakage Analysis through Inferring Apps in Smart Home IoT"
authors: [Yuan Luo, Long Cheng, Hongxin Hu, Guojun Peng, Danfeng Yao]
date: 2020-09-04T11:26:44+08:00
doi: "10.1109/JIOT.2020.3019812"

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-04T11:26:44+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "IEEE Internet of Things Journal"
publication_short: ""

abstract: "Emerging Internet of Things (IoT) systems leverage connected devices to enable intelligent and automated functionalities. Despite the benefits, there exist privacy risks of network traffic, which have been studied by the previous research. However, with the current privacy inference remaining at the event-level, potential privacy risks are underestimated, which, as our study shows, can be much higher than previously reported through app-level traffic analysis. A key observation of our research is that IoT event-triggered traffic is generated by apps, which often adopt an if-trigger-then-action (triggeraction) programming paradigm. We utilize this feature to develop fingerprints to differentiate running apps, and learn contextrich privacy-sensitive information from apps. In this paper, we present a privacy leakage analysis called ALTA to infer running apps in smart home IoT environments. First, ALTA identifies app fingerprints through static analysis, and extracts sensitive information from app descriptions and input prompts. Then, through dynamic traffic profiling, it learns traffic fingerprints of apps. Finally, ALTA matches the fingerprints of app and traffic, and thus is able to pinpoint which app is running from IoT traffic at runtime. To demonstrate the feasibility of our approach, we analyze 254 SmartThings applications via program and natural language processing (NLP) analysis. We also perform the app inference evaluation on 31 apps executed in a simulated smart home. The results suggest that ALTA can effectively infer running apps from IoT traffic and learn context-rich information (e.g., health conditions, daily routines, and user activities) from apps with high accuracy."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: Papers/smarthomeprivacy.pdf
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
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