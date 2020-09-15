---
title: Difference between float and flex
date: 2020-09-15 22:02:23
tags:
---

### **Float**

Float is a traditional solution which is separated from the document flow layout. It is based on the box model and relies on the `display` attribute, `position` attribute, and `float` attribute.

- Advantages:
  - It is very inconvenient for special layouts, such as vertical centering.

- Disadvantages:
  - Low error prone and high coupling. If one of the floating elements has some layout issues, other related elements will also be affected.
  - Fixed layout is required.
  - Not compatible for lower versions of Internet Explorer.

### **Flex**

Flex layout, which was carried out by W3C, can implement all kinds of web page layouts simply, completely and responsibly.

- Advantages:
  - The improvement of flex performance lies in that compared with traditional margin, it has strong scalability.
  - Compared with `float`, it has much more efficient correlation elements redrawing.
  - Less style control operation between child elements and parent elements than `tranform`.