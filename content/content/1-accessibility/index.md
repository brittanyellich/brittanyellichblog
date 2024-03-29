---
title: "Accessibility"
lastmod: 2022-11-13T00:00:00+08:00
draft: false
tags: [accessibility]
author: Brittany Ellich

toc:
  enable: true
  auto: true
---

[Notes](../../notes) / [Accessibility](./)

## Overview

### Why is accessibility important?

* Good accessibility is good design. It allows anyone to experience what you've made regardless of what technology they use.
* Understanding the tools used to enhance accessibility on the web as well as how a user may be limited will improve the abilities of developers and designers to build more accessibile websites.

## Links

* [Accessibility Layout](../1-a-accessibility-layout)
* [HTML Elements](../1-b-accessibility-html-elements)
* [Accessibility Testing](../1-c-accessibility-testing)

### ARIA

Accessible Rich Internet Applications (ARIA) provides a framework to make web components accessible. We provide simple ARIA attributes that are consumed by assistive technologies to convey information about widgets, structures, and behaviors. Always prefer the native HTML element to using an ARIA counterpart, where possible (ex. use `button type="button"` instead of `div role="button"`).

ARIA allows disabled users to interact with more complex applications by declaring the role of certain items on the page.

ARIA attributes are broken down into three categories:

1. Roles: Attributes that convey information about what an element is. Ex., `role="checkbox"` indicates that an element is a checkbox. There are many roles, like "alert", "dialog", "log", etc.
2. States: Attributes that convey the current state of an element. Ex., `aria-checked="true"` indicates that a checkbox is currently checked. Other examples are "aria-expanded", "aria-pressed", "aria-sort", etc.
3. Properties: Essential attributes that describe the nature of an element. Similar to states, but the primary difference is that properties are less likely to be dynamically updated. Ex. `aria-label="Terms and conditions"` informs the user that the element's accessible label is "Terms and conditions". Other examples include "aria-labelledby", "aria-describedby", "aria-owns", etc.

* [ARIA site](http://www.w3.org/TR/wai-aria/)

### Add-Ons

Some users will use add-ons, like Grease Monkey, to interact with your site and make it more readable for them, so making sure that your site is still usable with add-ons is a good idea.

### Design

* Avoid using `outline: none` as a blanket on the page. You'll have to go back in and add focus and it's easy to forget to add it to some elements on the page.

### Search

Include fuzzy checking or spell check on search for a user that may mispell a word

## Accessibility Standards

508 standards for the US government

Any others that we should be aware of?

## Learning Resources

### Courses

* [ ] [Gerard Cohen Courses on Pluralsight](https://gerardkcohen.me/courses/courses.html)
* [ ] [Accessibility for Web Design](https://www.linkedin.com/learning/accessibility-for-web-design/welcome?u=3322)
* [ ] [Deque Basic Web and Document Accessibility for Content Contributors](https://dequeuniversity.com/curriculum/courses/content-contributors)
* [ ] [Accessibility: Testing and Screen Reader Use](https://app.pluralsight.com/library/courses/accessibility-testing-and-screen-reader/table-of-contents)
* [ ] [Introduction to UX and Accessible Design](https://www.futurelearn.com/courses/introduction-to-ux-and-accessible-design)
* [ ] [Section 508 Trusted Tester](https://www.dhs.gov/trusted-tester)

### Articles

* [ ] [Deque: Accessibility in Design](https://www.deque.com/accessible-design/)
* [ ] [Deque: Accessibility in Development](https://www.deque.com/accessible-development/)
* [ ] [The Web Accessibility Introduction I wish I had](https://dev.to/maxwell_dev/the-web-accessibility-introduction-i-wish-i-had-4ope)
* [ ] [Comebacks for Five (Wrong) Arguments Against Accessibility](https://dev.to/maxwell_dev/comebacks-for-five-wrong-arguments-against-accessibility-5g5j)
* [ ] [Foundations: HTML Semantics](https://tetralogical.com/blog/2022/10/05/foundations-html-semantics/)
* [ ] [Is Your Organization Inclusive of Deaf Employees?](https://hbr.org/2022/10/is-your-organization-inclusive-of-deaf-employees)

### Videos

* [ ] [How Persons with Disabilities Use the Web](https://accessibility.deque.com/on-demand-how-persons-with-disabilities-use-the-web)
* [ ] [A11y cast series on Google Chrome developers channel](https://www.youtube.com/watch?v=HtTyRajRuyY&list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g)

### Books

* [ ] [Accessibility for Everyone by Laura Kalbag](https://abookapart.com/products/accessibility-for-everyone)
* [ ] [Practical Web Inclusion & Accessibility by Ashley Firth](https://learna11y.com/)
* [x] [Accessibility Handbook](https://www.oreilly.com/library/view/accessibility-handbook/9781449322847/)
