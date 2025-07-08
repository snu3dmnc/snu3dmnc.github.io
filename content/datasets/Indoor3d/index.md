---
title: Indoor Datasets

# event: Wowchemy Conference
# event_url: https://drive.google.com/drive/folders/1YXX3QZUGUeOL_rjC24_f65PC6gNsTqAR?usp=sharing

# location: Wowchemy HQ
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: Indoor Insta360 Captured datasets
# abstract: 'Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellusac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum. Sed ac faucibus dolor, scelerisque sollicitudin nisi. Cras purus urna, suscipit quis sapien eu, pulvinar tempor diam.'

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
publishDate: '2024-11-03T00:00:00Z'

authors: [SNU 3D Vision Lab.]
tags: []

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''
url_datasets: 'https://drive.google.com/file/d/18OXhSTDvlLEkqwTb_kzeIgGNr2d8XP9l/view?usp=share_link'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides:

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ''
---
[**Downloads**](https://drive.google.com/drive/folders/1YXX3QZUGUeOL_rjC24_f65PC6gNsTqAR?usp=share_link)

Capture with omnidirectional camera attached to a selfie stick
- Faster & easier capture than conventional camera (~1 min.)
- 5760 x 2880 resolution

Estimate camera poses
- Evenly sample frames
- Convert equirectangular images to cubemap images
- Run SfM with perspective images
(Worked better than run SfM directly on 360 images)