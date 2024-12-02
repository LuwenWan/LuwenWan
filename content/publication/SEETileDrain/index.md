---
title: "Mapping agricultural tile drainage in the US Midwest using explainable random forest machine learning and satellite imagery"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Anthony D Kendall
- Jeremy Rapp
- David W Hyndman


# Author notes (optional)

date: "2024-08-05T00:00:00Z"
doi: "https://doi.org/10.1016/j.scitotenv.2024.175283"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-08-05T00:00:00Z"

# Publication type.
# Legend: 
# 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: *Science of The Total Environment*

abstract: "There has been an increase in tile drained area across the US Midwest and other regions worldwide due to agricultural expansion, intensification, and climate variability. Despite this growth, spatially explicit tile drainage maps remain scarce, which limits the accuracy of hydrologic modeling and implementation of nutrient reduction strategies. Here, we developed a machine-learning model to provide a Spatially Explicit Estimate of Tile Drainage (SEETileDrain) across the US Midwest in 2017 at a 30-m resolution. This model used 31 satellite-derived and environmental features after removing less important and highly correlated features. It was trained with 60,938 tile and non-tile ground truth points within the Google Earth Engine cloud-computing platform. We also used multiple feature importance metrics and Accumulated Local Effects to interpret the machine learning model. The results show that our model achieved good accuracy, with 96 % of points classified correctly and an F1 score of 0.90. When tile drainage area is aggregated to the county scale, it agreed well (r2 = 0.69) with the reported area from the Ag Census. We found that Land Surface Temperature (LST) along with climate- and soil-related features were the most important factors for classification. The top-ranked feature is the median summer nighttime LST, followed by median summer soil moisture percent. This study demonstrates the potential of applying satellite remote sensing to map spatially explicit agricultural tile drainage across large regions. The results should be useful for land use change monitoring and hydrologic and nutrient models, including those designed to achieve cost-effective agricultural water and nutrient management strategies. The algorithms developed here should also be applicable for other remote sensing mapping applications."


tags: Agricultural tile drainage; Random forest classification; Feature importance; Google Earth Engine (GEE); LandsatUS; Midwest

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Online Appendix
# url: pdf/supplemental_information.pdf

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
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---

