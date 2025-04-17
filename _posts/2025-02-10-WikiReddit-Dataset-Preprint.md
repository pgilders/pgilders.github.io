---
layout: single
classes: wide
title:  "New WikiReddit Dataset Preprint"
date:   2025-02-10 09:02:00 +0000
tags: post preprint paper
author_profile: true

excerpt: "WikiReddit: Tracing Information and Attention Flows Between Online Platforms w/ Anna Beers, Viviane Ito, Agustin Orozco, and Francesca Tripodi"
header:
  teaser: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/wikireddit_abstract.png
  overlay_image: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/wikireddit_abstract.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background

gallery1:
  - url: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/wikireddit_table.png
    image_path: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/wikireddit_table.png
    alt: "A table from the paper detailing a summary of all Wikipedia mentions, those including links, and those that map to Wikipedia articles by Reddit format.

    | Posts | Comments | Total
    # mentioning Wikipedia | 335,897 | 10,264,340 | 10,600,237
    # with Wikipedia links | 286,359 | 9,465,316 | 9,751,675
    Total # of Wikipedia links | 658,493 | 11,573,36 | 12,231,860
    # unique Wikipedia links | 295,439 | 1,890,497 | 1,954,003
    # unique Wikipedia articles | 252,846 | 1,196,494 | 1,260,479."


gallery2:
  - url: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/posts_comments_over_time.png
    image_path: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/posts_comments_over_time.png
    alt: "Plot showing the daily count of posts and comments that mention Wikipedia (in text or as a link) over 2020-2023. The number of comments is steady at around 6000-7000, whereas the number of posts steadily decreases from around 300 to 200."
  - url: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/pageview_change_violin.png
    image_path: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/pageview_change_violin.png
    alt: "Figure showing the daily page views to Wikipedia articles on the day of posting and in the week after posting relative to the week before posting as a KDE plot. A small number of points in the extremes of the distributions are cut for visual clarity. We find that for links in Reddit posts, we observe a 45% increase in page views on the day of posting, and a 6% increase in the week after posting, as compared to the week before posting. For links in Reddit comments, we observe a 45% increase in page views on the day of posting, and a 5% increase in the week after posting, as compared to the week before posting."
  - url: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/en_proportion_vs_total.png
    image_path: assets/images/2025-02-10-WikiReddit-Dataset-Preprint/en_proportion_vs_total.png
    alt: "Figure showing the proportion of links to English Wikipedia from non-English Reddit posts vs the total number of links in that post language. Larger languages such as Chinese, German, French link to English Wikipedia around 20% of the time, whereas for smaller languages, English is used a majority of the time."

---


📄 Excited to share a new dataset preprint!

WikiReddit: Tracing Information and Attention Flows Between Online Platforms. A collaboration with Anna Beers, Viviane Ito, Agustin Orozco, and Francesca Tripodi.

📊 We introduce a new dataset of 12.2M Wikipedia links shared on Reddit over four years, offering a new lens on how two of the web’s most influential platforms interact.
- 📄 Preprint: [https://doi.org/10.48550/arXiv.2502.04942](https://doi.org/10.48550/arXiv.2502.04942)
- 💽 Dataset: [https://doi.org/10.5281/zenodo.14653265](https://doi.org/10.5281/zenodo.14653265)

Our dataset enables further research on:
- 📰 How Reddit drives attention to Wikipedia
- 🎭 Wikipedia’s (mis)use as a trusted source in online discourse
- ⚖️ How different communities engage with Wikipedia, revealing knowledge gaps
- 🔄 The interplay of demographic and platform biases on Reddit and Wikipedia


📂 The SQL database contains:
- All Reddit posts and comments mentioning Wikipedia 2020-23, including hyperlinks, hashed IDs, and metadata.
- Edit history and page view activity for Wikipedia articles at the time of posting, page IDs, and redirects.

{% include gallery id="gallery1" caption="" %}

👷 Care has been taken to omit and anonymise any potentially personally identifiable information. Future researchers with access to the Reddit and Wikipedia APIs can enrich their analyses by pulling extra data (e.g. post content) and linking to the processed cross-platform information provided here.

On exploratory analysis, we find:
- 📉 Declining activity in posts, but stable performance of Wikipedia content on Reddit
- 🔗 Strong correlations between Wikipedia and Reddit activity
- 🌍 Intriguing asymmetric patterns of cross-lingual linking, dominated by English

{% include gallery id="gallery2" caption=""%}

🙏 Thank you to Wikimedia Research and the reddit4researchers programme for the data access. I spoke more about this and other projects as part of the January Wikimedia research showcase, which you can watch here: [https://www.youtube.com/live/gvF8p4r91NE?t=2177s](https://www.youtube.com/live/gvF8p4r91NE?t=2177s)
