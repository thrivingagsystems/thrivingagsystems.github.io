---
_inputs:
  $.project-lead-logo:
    type: file
    comment: >-
      Use this image compression tool to make image between 300KB and 800KB. <a
      href="https://www.adobe.com/photoshop/online/compress-image.html"
      title="https://www.adobe.com/photoshop/online/compress-image.html"
      target="_blank">https://www.adobe.com/photoshop/online/compress-image.html</a>
  $.partner:
    type: array
    label: Partners
    comment: Add an image and link to partnering institutions.
    options:
      structures: _structures.partners-and-footer-partner
  $.project-sponsor-logo:
    type: file
    comment: >-
      Use this image compression tool to make image between 300KB and 800KB. <a
      href="https://www.adobe.com/photoshop/online/compress-image.html"
      title="https://www.adobe.com/photoshop/online/compress-image.html"
      target="_blank">https://www.adobe.com/photoshop/online/compress-image.html</a>
  $.description:
    type: html
    label: Footer Text
    comment: Add text here to display in the footer above the copyright notice.
  $.tracking-code:
    comment: Paste Tracking Code Here
partner:
- name: Ohio State
  image: assets/img/ohio_state_buckeyes_logo.jpg
  enable-image-link: false
  url: ''
- name: University of Maryland College Park
  image: assets/img/university_of_maryland_seal.jpg
  enable-image-link: false
  url: http://google.com
- name: Virginia Tech
  image: assets/img/vt.jpg
  enable-image-link: false
  url: http://google.com
- name: Stroud Water Research Center
  image: assets/img/stroud-black-bright-blue-2.jpg
  enable-image-link: false
  url: ''
- name: Utah State University
  image: assets/img/usu.jpg
  enable-image-link: false
  url: ''
description: "<p></p>"
project_lead_logo: assets/img/university-mark1-itok-yzyd-ebj.jpg
project-lead-description: ''
project-sponsor-logo: assets/img/usda-logo-color-1.jpg
project-sponsor-description: 'Project funded by USDA''s National Institute of Food
  and Agriculture '
project-lead-logo: assets/img/psu-mark.jpg
project-lead-link: ''
project-sponsor-link: ''
tracking-code: |-
  <!-- Global site tag (gtag.js) - Google Analytics -->

  <script async src="https://www.googletagmanager.com/gtag/js?id=G-RFJEY5FM58"></script>

  <script>

  window.dataLayer = window.dataLayer || [];

  function gtag(){dataLayer.push(arguments);}

  gtag('js', new Date());

  gtag('config', 'G-RFJEY5FM58');

  </script>

---
