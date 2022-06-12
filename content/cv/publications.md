---
# An instance of the Featured widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: portfolio

# This file represents a page section.
headless: true
active: false
# Order that this section appears on the page.
weight: 20

title: Publications
subtitle: ""

content:
  # Page type to display. E.g. project.
  page_type: publication

  # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below)
  filter_default: 0

  # Filter toolbar (optional).
  # Add or remove as many filters (`filter_button` instances) as you like.
  # To show all items, set `tag` to "*".
  # To filter by a specific tag, set `tag` to an existing tag name.
  # To remove toolbar, delete/comment all instances of `filter_button` below.
  filter_button:
    - name: All
      tag: '*'
    - name: Public Scholarship
      tag: 'Public Scholarship'
    - name: Journal Articles
      tag: 'article'
    - name: Book Chapters
      tag: 'book chapter'
    - name: Presentations
      tag: 'presentation'
    - name: Opinion Pieces
      tag: 'opinion'


#content:
  # Page type to display. E.g. post, talk, publication...
#  page_type: publication
  # Choose how many pages you would like to display (0 = all pages)
#  count: 0
  # Filter on criteria
#  filters:
#    author: ""
#    category: ""
#    publication_type: ""
#    tag: ""
  # Page order: descending (desc) or ascending (asc) date.
#  order: desc

#  filter_button:
#    - name: All Works
#      tag: '*'
#    - name: Undergraduate Level
#      tag: undergraduate
#    - name: Graduate Level
#      tag: graduate

design:
  # Choose a view for the listings:
  #   1 = List
  #   2 = Compact
  #   3 = Card
  #   4 = Citation (publication only)
  view: 1
  columns: "2"
---

<!--{{% callout note %}}
[Full publication list](./publication/) is available.
{{% /callout %}}-->
