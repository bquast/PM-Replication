---
title: 'Education, Education: Reproducible Research as a Pedagogical Tool'
author: "Danilo Freire and Bastiaan Quast"
date: '2014-11-24'
output: md_document
bibliography: bibliography.bib
---

## Introduction

The merits of reproducible research have already been widely acknowledged by political scientists (e.g., [@demesquita2003symposium]; [@king1995replication]; [@rich2013publishing]). Although replications are yet to appear more frequently in academic publications [@carsey2014making], there is a lively debate about how to make the discipline more open and reproducible. Here we discuss how graduate education plays an important yet overlooked role in improving transparency in political science research. We argue that the replication of a paper can serve as a guideline of good practices for pupils, and it is particularly relevant when students are making the transition from training to writing their first articles. We identify three key areas in which replications are specially helpful:

1) familiarise students with cutting-edge research tools;
2) experience the practical difficulties of research work;
3) help produce a publishable paper.

In the sections below we develop these ideas in further detail. We also present some practical tips for tutors who are willing to use replications as assignments in their lectures.


## Familiarise with research tools

One of the key benefits of replications is that is introduces students to current research practices. In many fields, the methodology is rapidly evolving often as a result of more data and data analysis tools.

Computation environments such the R statistical language [@R] or MatLab [-@MatLab] have greatly facilitated the development and implementation of new methods in both quantitative and qualitative research. Personally designed methods can be packaged and made publicly available. This had lead to a large rise in the number of algorithms being available, often written by the authors of the methods themselves.
However, non-commericial methods through which these software packages are distributed, combined with the vast number of them, can make it a somewhat daunting task determine the right software.

Replications generally concern published and peer-reviewed articles,
which means that the methods employed are proven to work
and have also undergone some review by the original author as well the reviewers.
This becomes especially useful when - as in most research - a combination of different methods is required.

Many research focused platforms have emerge over the past few years which can be very useful at the various stages of a research / replication project.

Public repository website such as GitHub - or self-hosted open-source equivalents such as GitLab or Gogs - offer a good place to host project remotely. There are several key advantages to this:

* a remote backup
* a well documented and timed claim to the research idea
* ability to work collaboratively on data analysis (e.g. .R files)

More recently, the rise of continuous integration tools such as Travil CI, have created the additional advantage that code can continuously be tested automatically. For a full discussion of continuous integration in reproducible research see Fitzjohn [-@fitzjohn2014reproducible].

During  the data analysis phase, working with combinations of different package can require quite some technical expertise, especially when a combination of different packages is required.
Q&A sites such as stackoverflow - and more recently the ones based o the open-source equivalent askbot, such as sagemath - allow users to post questions which can be answered by experiences other users (who gain reputation).
In addition to solving the direct issue of user posting, experienced users often offer other insights about, for instance,
additional problems in the approach,
new methods / tools that could be used,
interpretation of results.

In addition to Q&A sites, there are also platforms specifically dedicated to data interpretation.
Platforms such as Figshare or Plotly allow research output to be uploaded and shared with others, 
who can comment and suggest alternative ways of e.g. visualising the information.
Another interesting addition to the online visualisation scene is the R package shiny,
this package allows users to change elements of the visualisation using e.g. sliders in stead of fixed parameters.


## Practical Difficulties of Research

A good example is the replication of on the paper **Evaluating the Nuclear Peace Hypothesis** [@rauchhaus2009evaluating] done by Bell and Miller [-@bell2013questioning] provides an interesting example of how ....data separation...problem stata....


## Publish a paper

A finalised research project is only a first step towards a publishable research paper.
Following the example of the original paper, can help with structure, 


## References
