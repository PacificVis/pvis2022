---
title: 'Program'
permalink: '/test-sessions/'
---

{% include hide.md %}

| Day | Date | M/A | Sessions |
| ----- | -------------- | --------- | -------------------- |
| **Day 1** | April 11 (Mon) | Morning   | 9:00 [VISxAI 1](#visxai1), 11:10 [VISxAI 2](#visxai2)
|       |                | Afternoon | 14:30 [PVIS Opening](#opening), 15:00 [Keynote 1](#keynote1), 16:00 [Session 1](#session1)
| **Day 2** | April 12 (Tue) | Morning | 10:00 [Sessions 2](#session2), 11:30 [Session 3](#session3)
|       |                | Afternoon |  14:00 [Session 4](#session4), 16:00 [Session 5](#session5)
| **Day 3** | April 13 (Wed) | Morning   | 10:00 [Storytelling Contest](#contest), 11:30 [Session 6](#session6)
|       |                | Afternoon | 14:00 [Keynote 2](#keynote2), 14:50 [Posters](#posters), 16:30 [Banquet](#banquet)
| **Day 4** | April 14 (Thu) | Morning   | 10:00 [Sessions 7](#session7), 11:30 [Session 8](#session8), 12:30 [Closing](#closing)

{% assign session_period = "16:00-17:00, 10:00-11:00, 11:30-13:00, 14:00-15:30, 16:00-17:00, 11:30-13:00, 10:00-11:00, 11:30-12:30" | split: ", " %}

<p class="notice">Date/Time is presented in Japanese standard time (JST/UTC+9). More detail will be announced shortly.</p>

---

# Day 1 - April 11

## 9:00-10:40 - VISxAI Workshop 2022: Session 1 {#visxai1}

Chair: (TBA)

## 11:10-12:50 VISxAI Workshop 2022: Session 2 {#visxai2}

Chair: (TBA)

---
## 14:30-15:00 PacificVIS Opening {#opening}

## 15:00-15:30 Keynote 1 Q/A session {#keynote1}

Daniel Weiskopf on "[Multidimensional Visualization]({{ site.baseurl }}/program/keynotes/#danielweiskopf)"

<p class="notice">The keynote q/a starts with a brief explanation by Dr. Weiskopf followed by questions/answers.   Keynote talks will appear a few days before the opening on the conference YouTube channel.  You can discuss with Dr. Weiskopf realtime on Zoom or drop your messages on the `#keynote1` channel of the conference Discord a head of this session.</p>

{% assign accepted = site.data.accepted %}
{% assign index = accepted.index %}

---
# Day 2 - April 12

{% assign session_id = 0 %}
{% include test_tech_session.md %}

{% assign session_id = 1 %}
{% include test_tech_session.md %}

{% assign session_id = 2 %}
{% include test_tech_session.md %}

{% assign session_id = 3 %}
{% include test_tech_session.md %}

{% assign session_id = 4 %}
{% include test_tech_session.md %}

---
# Day 3 - April 13

# 10:00-11:00 Visual Data Storytelling Contest {#contest}

{% assign session_id = 5 %}
{% include test_tech_session.md %}

# 14:00-14:30 Keynote 2 {#keynote2}

Wei Chen on "[When Visualization Meets Privacy]({{ site.baseurl }}/program/keynotes/#weichen)"

<p class="notice">The keynote q/a starts with a brief explanation by Dr. Chen followed by questions/answers.  Keynote talks will appear a few days before the opening on the conference YouTube channel.  You can discuss with Dr. Chen realtime on Zoom or drop your messages on the `#keynote1` channel of the conference Discord a head of this session.</p>

# 14:50-16:20 Posters {#posters}

Posters will take place on a Gather.Town room.

# 16:30-17:30 Virtual Banquet {#banquet}

Virtual banquet will take place on a Gather.Town room.

---
{% assign session_id = 6 %}
{% include test_tech_session.md %}

{% assign session_id = 7 %}
{% include test_tech_session.md %}

# 12:30-13:00 Closing {#closing}

<script src="https://unpkg.com/vue@3"></script>
<script type="text/javascript" src="/pvis2022/assets/javascripts/accepted.json.js"></script>
<script type="text/javascript" src="/pvis2022/assets/javascripts/preview.json.js"></script>
<script type="text/javascript" src="/pvis2022/assets/javascripts/accepted.js"></script>
