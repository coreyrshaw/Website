---
permalink: /smm_bc/
title: "Social Media Mining for Breast Cancer Research"
excerpt: "Outline of our work on breast cancer research"
layouts_gallery:
  - url: /assets/images/mm-layout-splash.png
    image_path: /assets/images/mm-layout-splash.png
    alt: "splash layout example"
  - url: /assets/images/mm-layout-single-meta.png
    image_path: /assets/images/mm-layout-single-meta.png
    alt: "single layout with comments and related posts"
  - url: /assets/images/mm-layout-archive.png
    image_path: /assets/images/mm-layout-archive.png
    alt: "archive layout example"
last_modified_at: 2019-08-27T15:46:43-04:00
toc: true
---

## Overview
Breast cancer patients often discontinue their long-term treatments, such as hormone therapy, increasing the risk of cancer recurrence. 
These discontinuations are often caused by adverse patient-centered outcomes (PCOs) due to hormonal drug side effects or other factors. 
PCOs are not detectable through laboratory tests, and are sparsely documented in electronic health records. 
Thus, there is a need to explore other sources of information for PCOs associated with breast cancer treatments. 
Social media is a promising resource, but extracting true PCOs from it first requires the accurate detection of breast cancer patients. 
We describe a natural language processing (NLP) architecture for automatically detecting breast cancer patients from Twitter based on their self-reports. 
The architecture employs breast cancer related keywords to collect streaming data from Twitter, applies NLP patterns to pre-filter noisy posts, and then employs a machine learning classifier trained using manually-annotated data (n=5019) for distinguishing firsthand self-reports of breast cancer from other tweets. 
A classifier based on bidirectional encoder representations from transformers (BERT) showed human-like performance and achieved F1-score of 0.857 (inter-annotator agreement: 0.845; Cohen's kappa) for the positive class, considerably outper-forming the next best classifier--a deep neural network (F1-score: 0.665).
Qualitative analyses of posts from automatically-detected users revealed discussions about side effects, non-adherence and mental health conditions, illustrating the feasibility of our social media-based approach for studying breast cancer related PCOs from a large population.

<!-- - Bundled as a "theme gem" for easier install/upgrading.
- Compatible with GitHub Pages.
- Support for Jekyll's built-in Sass/SCSS preprocessor.
- Nine different skins (color variations).
- Several responsive layout options (single, archive index, search, splash, and paginated home page).
- Optimized for search engines with support for [Twitter Cards](https://dev.twitter.com/cards/overview) and [Open Graph](http://ogp.me/) data
- Optional [header images](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#headers), [custom sidebars](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#sidebars), [table of contents](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#table-of-contents), [galleries](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#gallery), related posts, [breadcrumb links](https://mmistakes.github.io/minimal-mistakes/docs/configuration/#breadcrumb-navigation-beta), [navigation lists](https://mmistakes.github.io/minimal-mistakes/docs/helpers/#navigation-list), and more.
- Commenting support (powered by [Disqus](https://disqus.com/), [Facebook](https://developers.facebook.com/docs/plugins/comments), [Discourse](https://www.discourse.org/), [utterances](https://utteranc.es/), static-based via [Staticman v1 and v2](https://staticman.net/), and custom).
- [Google Analytics](https://www.google.com/analytics/) support.
- UI localized text in English (default), Brazilian Portuguese (Português brasileiro), Catalan, Chinese, Danish, Dutch, French (Français), German (Deutsch), Greek, Hindi (हिंदी), Hungarian, Indonesian, Italian (Italiano), Japanese, Korean, Malayalam, Nepali (Nepalese), Persian (فارسی), Polish, Punjabi (ਪੰਜਾਬੀ), Romanian, Russian, Slovak, Spanish (Español), Swedish, Thai, Turkish (Türkçe), and Vietnamese. -->




<!-- | Name                                        | Description                                           |
| ------------------------------------------- | ----------------------------------------------------- |
| [Post with Header Image][header-image-post] | A post with a large header image. |
| [HTML Tags and Formatting Post][html-tags-post] | A variety of common markup showing how the theme styles them. |
| [Syntax Highlighting Post][syntax-post] | Post displaying highlighted code. |
| [Post with a Gallery][gallery-post] | A post showing several images wrapped in `<figure>` elements. |
| [Sample Collection Page][sample-collection] | Single page from a collection. |
| [Categories Archive][categories-archive] | Posts grouped by category. |
| [Tags Archive][tags-archive] | Posts grouped by tag. |

For even more demo pages check the [posts archive][year-archive].

[sample-collection]: {{ "/recipes/chocolate-chip-cookies/" | relative_url }}
[categories-archive]: {{ "/categories/" | relative_url }}
[tags-archive]: {{ "/tags/" | relative_url }}
[year-archive]: {{ "/year-archive/" | relative_url }} -->

---




<!-- ### Icons + Demo Images:

- [The Noun Project](https://thenounproject.com) -- Garrett Knoll, Arthur Shlain, and [tracy tam](https://thenounproject.com/tracytam)
- [Font Awesome](http://fontawesome.io/)
- [Unsplash](https://unsplash.com/)

### Other:

- [Jekyll](https://jekyllrb.com/)
- [jQuery](https://jquery.com/)
- [Susy](http://susy.oddbird.net/)
- [Breakpoint](http://breakpoint-sass.com/)
- [Magnific Popup](http://dimsemenov.com/plugins/magnific-popup/)
- [FitVids.JS](http://fitvidsjs.com/)
- Greedy Navigation - [lukejacksonn](https://codepen.io/lukejacksonn/pen/PwmwWV)
- [jQuery Smooth Scroll](https://github.com/kswedberg/jquery-smooth-scroll)
- [Lunr](http://lunrjs.com)

---

Minimal Mistakes is designed, developed, and maintained by Michael Rose. Just another boring, tattooed, designer from Buffalo New York. -->
