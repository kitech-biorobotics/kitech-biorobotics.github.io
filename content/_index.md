---
title:
date: 2022-10-24
type: landing

sections:
  - block: hero
    content:
      title: |
        KITECH
        Bio-Robotics Lab
      image:
        filename: welcome.jpg
      text: |
        <br>

        The **KITECH Bio-Robotics Lab** advances research in biomechatronics and wearable robotics for human assistance, including advanced robotic actuator technologies and data-driven human motion sensing and understanding.

  - block: collection
    content:
      title: Latest News
      count: 3
      page_type: post
      sort_by: Params.event_date
      sort_ascending: false
      filters:
        folders:
          - post
    design:
      view: compact
      columns: "1"
      css_class: news-clean

  - block: markdown
    content:
      title:
      subtitle:
      text: |
        Our research spans wearable robotics, biosignal interfaces, robotic actuation, tactile sensing, and data-driven human motion understanding.
        {{% cta cta_link="./people/" cta_text="Meet the team →" %}}
    design:
      columns: "1"
---
