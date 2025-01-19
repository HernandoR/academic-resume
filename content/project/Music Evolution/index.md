---
title: Full color FDM 3D Printer with Machine Learning Feedback
summary: |-
    - Developed Multiple models to quantify musical influence;
    - Applied RNN neural network to analyze the development of “music’s impact on network” in time series; 
    - Received Meritorious Winner Prize.


tags:
  - Mathematical modeling
  - RNN
date: '2021-04-26'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Artists-based_similarity_compare
  focal_point: Smart

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
url_code: ''
url_pdf: 'Reports/ICM_2021.pdf'
url_slides: ''
url_video: ''

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: example
---

<!-- # Related Outputs and Honors -->
# Summary
The existence and development of music is not only the law and problem of music itself, it develops with the change of human society and culture, and various styles of music communicate and integrate with each other. In order to quantify this process and understand music culture, we have developed the `Music Influence Network` and `Music Similarity Measure` models, as well as other models to measure such issues as music influence.

In order to establish a `Music Influence` model to evaluate the comprehensive influence of artists, we constructed a targeted `music influence network`. Considering the lack of time dimension information, we constructed a 'genre-period relationship curve' as a supplement. In the model, the concept of hierarchy is more prominent, and the selected parameter of `music influence` has a distinct attribute that makes it possible to be layered. The hierarchical nature of the parameters allows the Musical Impact model to judge artists from different perspectives. For example, using this model, we can find `revolutionary artists` within each genre by increasing the weight of parameters in the `musical influence` parameter that are more representative of genres and more reflective of development.

To address the problem of measuring musical similarity, we note that distance and similarity should satisfy restrictions such as non-negativity, triangular inequality, and neighbourhood correlation, and propose a similarity measure based on Euclidean distance.

We have carried out calculation and analyses based on similarity above to study the differences between genres and the changes in genres over time. It shows that artists' similarity within genres is generally more significant than that of artists between genres, while musical genres influence each other to converge.

In determining whether influencers have influenced the music created by their followers, we note that the 'Musical Similarity Measure' model is challenging to interpret for a single object. We innovatively use the idea of 'Mismatch' by comparing the mean values of similarity in influence pairs, to those who are not. We are confident that influencers have a strong influence on the music created by their followers.

To investigate the `contagious` of each music characteristics, we considered the `contagious of music Characteristics` factor, using existing models, and concluded that musical characteristics do not have a consistent `contagious`.

Finally, considering that music's evolution is related to the artist and involves many non-musical factors, such as social, political, technological, we analyse music as a culture to understand its change and development. The research proves that music changes mainly in response to the evolution and development of society.
