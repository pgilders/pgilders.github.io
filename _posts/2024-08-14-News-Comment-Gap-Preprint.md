---
layout: single
classes: wide
title:  "New Preprint on the News Comment Gap"
date:   2024-08-14 11:08:00 +0000
tags: post preprint paper
author_profile: true

excerpt: "The News Comment Gap and Algorithmic Agenda Setting in Online Forums w/ Flora Böwing"
header:
  teaser: assets/images/2024-08-14-Comment-Gap-Preprint/comment-gap-abstract.png
  overlay_image: assets/images/2024-08-14-Comment-Gap-Preprint/comment-gap-abstract.png
  overlay_filter: 0.5 # same as adding an opacity of 0.5 to a black background

gallery1:
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/comment-gap-abstract.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/comment-gap-abstract.png
    alt: "Screenshot of paper title and abstract."
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/pinvscompoundcomment.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/pinvscompoundcomment.png
    alt: "Figure showing the difference in comment preferences between journalists and readers."
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/FORUM_tweet_example.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/FORUM_tweet_example.png
    alt: "Figure showing the distribution of FORUM scores for Lexical Diversity over the first 10 comments for different ranking algorithms."

gallery2:
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/pinvscompoundcomment.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/pinvscompoundcomment.png
    alt: "Figure showing the difference in comment preferences between journalists and readers."

gallery3:
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/sorting_performance.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/sorting_performance.png
    alt: "Figure showing how FORUM score is calculated."

gallery4:
  - url: assets/images/2024-08-14-Comment-Gap-Preprint/qdist_best_default_worst.png
    image_path: assets/images/2024-08-14-Comment-Gap-Preprint/qdist_best_default_worst.png
    alt: "Figure showing the distribution of FORUM scores for several features over the first 10 comments and full discussion for different ranking algorithms."

---


🚨New preprint!

📰The News Comment Gap and Algorithmic Agenda Setting in Online Forums w/ Flora Böwing

We study:
1. The differences in comment preferences between journalists and readers
2. How comment ranking algorithms prioritise different kinds of comments to display to users

{% include gallery id="gallery1" layout="third" caption="" %}

🕵️With data from DER STANDARD, we find, compared to readers, journalists prefer more positive, timely, complex, direct responses, while readers favour comments similar to article content from elite authors.

{% include gallery id="gallery2" caption=""%}{: .align-center .width-50}

📈We develop the Feature-Oriented Ranking Utility Metric (FORUM 🥁) to evaluate how well a ranking algorithm (most upvoted, chronological, etc) returns comments by a certain feature (sentiment, readability, etc) compared to best/worst-possible and random baseline.

{% include gallery id="gallery3" caption=""%}{: .align-center .width-50}

🛠️FORUM is a versatile, interpretable tool that can be applied to any task of scoring how well a set of items are sorted, far more than just news comments!

🔍With FORUM, we find dramatic differences in how different, even simple, algorithms prioritise different kinds of comments, as measured by their sentiment, readability, lexical diversity, and similarity to the article.

{% include gallery id="gallery4" caption=""%}{: .align-center .width-50}

💪We thus argue editors can exercise agenda setting power in comment sections through curational and algorithmic means.
The effects on how audience reception to an article is represented by ranking algorithms are larger than those from more traditional measures (e.g. Editor Picks).

🗣️Understanding these preferences and algorithmic consequences is vital in fostering healthy discussion online and of clear interest to journalists presenting their stories.
This is especially important given the increasing scrutiny of online speech and how it is hosted/moderated.

👨‍🏫I presented this work at IC2S2 2024.
📖To find out more, check out the following:
🔗Preprint link: [https://arxiv.org/abs/2408.07052](https://arxiv.org/abs/2408.07052)
🐍Try FORUM in Python: [https://github.com/pgilders/pyforum](https://github.com/pgilders/pyforum)

🌟Finally, big thanks to Flora, this project came out of her prizewinning work at LSE Methodology!
