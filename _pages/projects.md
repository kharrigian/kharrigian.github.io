---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

{% include base_path %}

On this page, you will find projects I have worked on whose code/data is in a publicly releasable state. Feel free to check out my Github profile for other work-in-progress projects. 

## Geolocation Inference for Reddit

Based on my 2018 W-NUT [<span style="color:blue">paper</span>](http://aclweb.org/anthology/W18-6103), I have open-sourced code, models, and data to infer the home location of Reddit users. While the repository is freely-available, there are certain restrictions on its usage. Please read through the README and License [<span style="color:blue">here</span>](https://github.com/kharrigian/smgeo) to see if this tool will work for you!

## Pushshift.io API Wrapper

The [<span style="color:blue">pushshift.io project</span>](https://pushshift.io) has served as a valuable resource to researchers and industry practitioners alike, offering nearly complete access to public-facing Reddit data. One of the primary interfaces to the backend database is the Python package [<span style="color:blue">PSAW</span>](https://pypi.org/project/psaw/). While this package is extremely useful for handling low-level complexities of the pushshift.io database (e.g. pagination), it lacks some of the high-level abstractions that are commonly of interest when retrieving and manipulating Reddit data. To lower the barrier to entry of analyzing well-formatted Reddit data, I have open-sourced my personal library of utility functions for `PSAW` (and `PRAW`) [<span style="color:blue">here</span>](https://github.com/kharrigian/retriever).

## Mental Health Datasets

There has been tremendous interest in using social media to monitor individual- and population-level mental health. At the forefront of this research is clean, clinically-relevant data. To help researchers interested in this area identify the dataset that is appropriate for answering their research questions, I have compiled and annotated a large directory of existing datasets [<span style="color:blue">here</span>](https://github.com/kharrigian/mental-health-datasets). This directory will be updated over time as new literature is published. If you are interested in contributing to this resource, please reach out using one of the contact mechanisms in the sidebar.

## Mental Health Keywords

Identifying statements related to mental health in social media is one straightforward approach to monitoring population-level mental health over time. For certain platforms (e.g. Twitter), obtaining historical data is difficult or even impossible. Instead, it is necessary to capture relevant posts in a constantly-monitored stream. To support this goal, I have compiled a list of n-grams that are likely to be used by individuals when discussing their mental health. This list was curated using a combination of automatic (i.e. Pointwise Mutual Information) and manual methods based on data from commonly adopted Twitter datasets for mental health research. The list can be found [<span style="color:blue">here</span>](https://github.com/kharrigian/mental-health-keywords) and will be updated over time as its validity is quantified.

## Subreddit Recommendation Engine (Language Aware)

The social media platform Reddit is structured as a pool of thematically-distinct communities. Most tools used for recommending new communities (i.e. subreddits) leverage post-activity to identify users who share similar interests. However, these tools often do not explicitly factor in the language distribution within a community when making a recommendation. For users who are non-native English speakers or are interested in learning a second-language, discovering subreddits where they can communicate in a given language may improve their engagement with the platform. To support this goal, I have developed [<span style="color:blue">code and models</span>](https://github.com/kharrigian/rrec) that make content- and language-aware subreddit recommendations.

## Pitchers and Pianists (HMM-based Tap Detection)

I had the opportunity to co-supervise a study at the Boston Museum of Science in 2015 that sought to understand rhythmic tendencies across a cross-sectional demographic pool. Specifically, we examined the ability for individuals to tap their finger consistently to a beat without the assistance of a metronome. Unlike previous lab-based studies, we found data from this study to be quite noisy and unmanageable for existing tools. Our ultimate solution involved the use of an HMM to detect taps in digital signal in an unsupervised manner. Code (and scripts used for analysis of the study) can be found [<span style="color:blue">here</span>](https://github.com/kharrigian/pitchers-and-pianists).