---
title: "Post 3"
date: 2021-09-05T19:54:45+07:00
draft: false
description : "It is a long established fact that a reader will be distracted by the readable content of a page when looking at its layout. The point of using Lorem Ipsum is that it has a more-or-less normal distribution of letters, as opposed to using 'Content here, content here', making it look like readable English. Many desktop publishing packages and web page editors now use Lorem Ipsum as their default model text, and a search for 'lorem ipsum' will uncover man"
featured_image : "https://i.imgur.com/eROlKpP.png"
---


---
title: "Elements showcase"
date: 2015-05-28
categories:
- tranquilpeak
- features
tags:
- html elements
- markdown
thumbnailImagePosition: left
thumbnailImage: //d1u9biwaxjngwg.cloudfront.net/elements-showcase/vintage-140.jpg
---

Check out how Tranquilpeak theme display well HTML elements (title, paragraph, blockquote, table and more..). It's simple and elegant.
<!--more-->

# heading # { .className attrName=attrValue class="text-6xl press-start"}
heading 1
## heading ## { .className attrName=attrValue class="text-5xl press-start"}
heading 2
### heading ### { .className attrName=attrValue class="text-4xl press-start"}
heading 3
#### heading #### { .className attrName=attrValue class="text-3xl press-start"}
heading 4
##### heading ##### { .className attrName=attrValue class="text-2xl press-start"}
heading 5
###### heading ###### { .className attrName=attrValue class="text-xl press-start"}
heading 7

```go {.press-start linenos=table,hl_lines=[8,"15-17"],linenostart=1}
{{ define "main" }}

<div class="w-5/6   lg:max-w-screen-xl  mx-auto nes-container mt-5 is-dark member-card"><div class="avatar">
  <h4 class="topic-title text-xl press-start"><i class="nes-icon star"></i>My Portofolio</h4>
   </div>
  </div>


 {{ template "_internal/pagination.html" . }}
 
{{ end }}
```





![Text](https://d33wubrfki0l68.cloudfront.net/c38c7334cc3f23585738e40334284fddcaf03d5e/2e17c/images/hugo-logo-wide.svg "Title")


Lorem ipsum dolor sit amet, [test link]() consectetur adipiscing elit. **Strong text** pellentesque ligula commodo viverra vehicula. *Italic text* at ullamcorper enim. Morbi a euismod nibh. <u>Underline text</u> non elit nisl. ~~Deleted text~~ tristique, sem id condimentum tempus, metus lectus venenatis mauris, sit amet semper lorem felis a eros. Fusce egestas nibh at sagittis auctor. Sed ultricies ac arcu quis molestie. Donec dapibus nunc in nibh egestas, vitae volutpat sem iaculis. Curabitur sem tellus, elementum nec quam id, fermentum laoreet mi. Ut mollis ullamcorper turpis, vitae facilisis velit ultricies sit amet. Etiam laoreet dui odio, id tempus justo tincidunt id. Phasellus scelerisque nunc sed nunc ultricies accumsan.

Interdum et malesuada fames ac ante ipsum primis in faucibus. `Sed erat diam`, blandit eget felis aliquam, rhoncus varius urna. Donec tellus sapien, sodales eget ante vitae, feugiat ullamcorper urna. Praesent auctor dui vitae dapibus eleifend. Proin viverra mollis neque, ut ullamcorper elit posuere eget.


## List Types

### Definition List (dl)

<dl><dt>Definition List Title</dt><dd>This is a definition list division.</dd></dl>

### Ordered List (ol)

1. List Item 1
2. List Item 2
3. List Item 3

### Unordered List (ul)

- List Item 1
- List Item 2
- List Item 3

## Table

|  Header 1  | Header 2   | Header 3   |
|:----------:|------------|------------|
| Division 1 | Division 2 | Division 3 |
| Division 1 | Division 2 | Division 3 |
| Division 1 | Division 2 | Division 3 |
| Division 1 | Division 2 | Division 3 |

## Misc Stuff - abbr, acronym, sub, sup, etc.

Lorem <sup>superscript</sup> dolor <sub>subscript</sub> amet, consectetuer adipiscing <kdb>ctrl + c</kdb>. Nullam dignissim convallis est. Quisque aliquam. <cite>cite</cite>. Nunc iaculis suscipit dui.
 Nam
sit amet sem. Aliquam libero nisi, imperdiet at, tincidunt nec, gravida vehicula, nisl. Praesent mattis, massa quis luctus fermentum, turpis mi volutpat justo, eu volutpat enim diam eget metus. Maecenas ornare tortor. Donec sed tellus eget sapien fringilla nonummy. <acronym title="National Basketball Association">NBA</acronym> Mauris a ante. Suspendisse quam sem, consequat at, commodo vitae, feugiat in, nunc. Morbi imperdiet augue quis tellus.  <abbr title="Avenue">AVE</abbr>
