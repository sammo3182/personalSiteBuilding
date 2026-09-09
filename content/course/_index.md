---

# for listing page layout
layout: list-sidebar # list, list-sidebar

# for list-sidebar layout
sidebar:
  title: Teaching 教学
  description: |
    I teach substantive courses in political science and methodological courses in computational social science.
    The right-hand section lists both series, with a brief description of each course and a link to its lecture slides.
    Courses not currently on offer are marked as such.
    Feel free to reach out for additional information.

    我讲授政治科学的专业课程与计算社会科学的方法课程。
    页面右侧列出这两个系列的全部课程，附简要介绍及课件链接。
    当前未开设的课程会另行标注。
    若需要更多信息，请随时与我联系。
  show_sidebar_adunit: false # show ad container

# set up common front matter for all pages inside blog/
cascade:
  type: blog
  author: "HU Yue"
  show_post_thumbnail: true
  show_author_byline: false
  # A course is not a dated post. The `date:` values below only order the pages;
  # displaying them made every course read as last touched in 2021.
  show_post_date: false
  show_post_time: false
  show_disqus_comments: false # see disqusShortname in site config
  # for single-sidebar layout
  # sidebar:
  #   text_link_label: View recent talks
  #   text_link_url: /talk/
  #   show_sidebar_adunit: false # show ad container
---

** No content below YAML for the talk _index. This file provides front matter for the listing page layout and sidebar content. It is also a branch bundle, and all settings under `cascade` provide front matter for all pages inside talk/. You may still override any of these by changing them in a page's front matter.**
