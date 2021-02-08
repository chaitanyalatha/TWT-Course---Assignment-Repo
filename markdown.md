---
layout: demo
title: Markdown Overview
---

# {{page.title}}

<p> The overriding design goal for *Markdown*’s formatting syntax is to make it as readable as possible. The idea is a *Markdown* formatted document should be publishable as-is, as plain text, without looking like it’s been marked up with tags or formatting instructions.

<p> The philosophy behind *Markdown* is that plain text documents should be readable without tags mussing everything up. You can use *markdown* to add formatting elements to plaintext documents.</p>

### Markdown Syntax


| Markdown Element | Syntax |

| ------ | ------ |
| Heading level 1 | # |
| Heading level 2 to Heading 6 | ## to ###### |
| Paragraph | <p> |
| Bold | ** |
| Italic | * |
| Unordered list | - |
| Ordered list | any number, followed by at least2 space |


#### Best Practices

- Always put a space between the number signs (#) and the heading name.
- Unless the paragraph is in a list, don’t indent paragraphs with spaces or tabs.
- For Line break, use trailing white space or the <br> HTML tag at the end of the line.
- Put blank lines before and after horizontal rules.

Show the time: {{ site.when }}

Data file contents:

{% for item in site.data.demo %}

{{ site.data.demo }}

{% endfor %}
