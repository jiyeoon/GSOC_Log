---
layout: page
title: About This Blog
permalink: /about
---

![img](https://www.embecosm.com/app/uploads/gsoc.png)

Hi! I'm [Jiyeon Lee](https://github.com/jiyeoon) from South Korea. 🇰🇷

This blog is for recording my [GSOC(Google Summer of Code)](https://summerofcode.withgoogle.com/) project, which is **TFLite GPU inference latency estimator on mobile device.**

<br/>

## Abstract

Currently there is no simple way for inference time estimation when prototyping the neural network model. It is common to design the new architecture keeping some principle of GPU-friendly model in mind. But to understand how the newly prototyped model will perform on the GPU, developers need to actually execute inference on many phones manually.

This project aims to solve this issue by building a tool for an offline model latency estimation. To make this possible the database with a variety of benchmarks will be created and then analyssed with specially developed jeuristics and regression methods. As a stretch goal, integration with some neural network visualizer may be implemented when the tool is ready.

<br/>

## Project Timeline

- First part of the coding time
  - Week 1 (June 7-14) : understand how the convolutions need to be generated
  - Week 2 (June 14-21) : have one-convolution models generated
  - Week 3 (June 21-28) : collect initial benchmarks, start designing the database
  - Week 4 (June 28-July 5) : implement an estimator which uses simple regression
  - Week 5 (July 5-12) : buffer week
  - **Expectaion from the first coding time part : the initial version of both database and latency estimation tools**
- Second part of the coding time
  - Week 6 (July 12-19) : analyze what was missed in the database
  - Week 7 (July 19-26) : adjust database with an updated set of convolutions
  - Week 8 (July 26 - August 2) : time for perfecting the latency estimator
  - Week 9 (August 2-9) : buffer week (maybe integrate with NN visualizer)
  - Week 10 (August 9-16) : prepare documentation, last code polishments, etc
  - **Expectaion from the second coding time part : project deliverable is reached + tested on the known networks + docs**
- Code submissions, presentations, etc
  - Week 11 (August 16-23) : students submit their code and evaluations
  - Week 12 (August 23-30) : mentors submit final evaluations
  - August 31 - Results are announced

