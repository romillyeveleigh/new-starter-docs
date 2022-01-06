---
title: Accessibility Post
date: 2022-01-06T17:19:32.169Z
description: How to make sure your code follows the rules for accessibility?
---

How to make sure your code follows the rules for accessibility

### Installation

Please install screen reader on your device. We recommend
NVDA
(Windows), VoiceOver
(MacOS and iOS) and TalkBack (Android).
Once it is installed, start the NVDA application and you are ready to go with your screen
reader.

### Introduction

An example of accessibility would be any content or functionality that is fully available to
and usable by people with disabilities.

Slack channel for Accessibility:
a11y-community
WCAG (Web Content Accessibility Guidelines) 2.0 guidelines are categorized into three
levels of conformance in order to meet the needs of different groups and different situations:
A (lowest), AA (mid-range), and AAA (highest).
We at least follow WCAG AA throughout our application and WCAG AAA whenever asked
for.

Our app should follow at least the below mentioned criteria’s:

1.  Every form control has an associate label:
    [link](https://www.w3.org/WAI/tips/developing/#associate-a-label-with-every-form-control)
2.  Alt Attributes are present for all images, regardless of being empty of not:
    Approach: Ensure that alternative text for images is added to all informational and
    functional images. Use empty alternative text, alt="" for decorative images, or include
    them in the CSS instead. Text alternatives are usually provided by those responsible
    for written content.
    [link](https://www.w3.org/WAI/tips/developing/#include-alternative-text-for-images)
3.  Language of page and language of parts are identified:
    [link](https://www.w3.org/WAI/tips/developing/#identify-page-language-and-language-changes)

