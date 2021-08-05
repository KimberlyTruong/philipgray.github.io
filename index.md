---
layout: home
title: 
permalink: 
---

According to GitHub's <a href="https://opensourcesurvey.org/2017/">2017 Open Source Survey</a>, of the software developers (and related positions) surveyed, they found that:
* 94% reported using open source in their professional work
* 84% reported having dependencies in their code base

Recent research into Open Source has been about trying to calculate the "truck factor" of a project. While it's a fairly grim term, "truck factor" or "bus factor" is thrown around a lot in the software industry. Truck/bus factor means, <a href="http://www.agileadvice.com/2005/05/15/agilemanagement/truck-factor/">“The number of people on your team who have to be hit with a truck before the project is in serious trouble.”</a> This research has shown (while not incredibly reliable) that many open source projects have a very low "truck factor" which suggests that they're in danger if something were to happen to contributors. Rather than worrying about the chances someone is going to get hit by a  truck or bus, we felt it's important to look into why people disengage from these projects instead.

There's been some research as well on disengagement in Open Source but none of which have utilized gray literature until now. By analyzing blogposts, tweets, podcasts, conference talks, we get a more unfilitered, and often raw look at what motivates people to leave. 

# Methodology

We conducted an analysis of two different mediums of gray literature, text-based (blog posts, emails, and tweets) and audiovisual-based (recorded conference talks, and podcasts) in order to better our understanding of why contributors disengage. 

## Text-based Literature

For text-based literature, we did the following to collect the data:

* Created a list of blog posts, tweets, emails, and articles related to Open Source
  * Searched the top ten pages of results for Google for a variety of keywords
* Filtered out results that did not mention disengagement
* Replaced third party explanations with first party
  * E.g. Changing from news articles about contributors disengaging to the actual post by the contributor

## Audiovisual-based Literature

For audiovisual-based literature, we split our methods up into two. 

### Conference Talks

We did the following for the talks:

* Using our own knowledge of Open Source conferences, and the top 30 Google search results for "Open Source Conference" we compiled a list of conferences
* Using the YouTube Data API, got the title, publication date, and video IDs for videos related to the list of conferences we collected
* Fed the video IDs into the PyTube API in order to download the automatically transcribed transcripts from YouTube
* Used a scoring system to help filter out videos based on keywords found in the video's transcripts. 

### Podcasts

We did the following for podcasts:

* Used the iTunes Podcast API to get the first 200 podcasts with the keywords, "open source"
* For each podcast, we downloaded the RSS feed and got each episode description
* We then used a scoring system to filter out episodes.
* Transcribed the episodes

## Coding

After we've filtered our results, we began coding. We used a two-step coding approach. 

### First Pass

During the first pass, we tagged every single reason why contributor were disengaging or factors that were related to the contributor's disengagement. 

### Second Pass

The second pass was similar to the first pass, instead we looked for similar codes that could be combined. For example, the codes "Bullying" and "Toxicity" became "Community Hostility."

# Results

For each contributor, we have a post with the various codes and a summary of why they disengaged which can be found <a href="\directory">here</a>. The individual codes can be found <a href="\codes">here</a>, and the codebook with the descriptions <a href="\codebook">here</a>. 



