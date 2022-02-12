---
layout: single
title: 'Uma Musume Mirai'
categories: "Craft_with_SmartDoll"
comments : true
tag: [Doll, Mirai_Suenaga]
og_image: /images/og_image/og_image_Mirai.jpg
#toc: #true #true로 시키면 목차가 만들어 집니다.
author_profile: false #false 시키면 저자 프로파일 사라집니다. true면 켜져요.
#search: #false #false면 서치기능에서 활용이 안됩니다.
sidebar:
    nav: "docs1"
---
{% if page.is_post %}
  {% assign type = "article" %}
{% else %}
  {% assign type = "website" %}
{% endif %}
  <meta property="og:type" content="{{ type }}" />
  <meta property="og:url" content="{{ page.url | replace:'index.html','' | prepend: site.baseurl | prepend: site.url }}" />
  <meta property="og:title" content="{% if page.title %}{{ page.title }}{% else %}{{ site.title }}{% endif %}" />
  <meta property="og:description" content="{% if page.excerpt %}{{ page.excerpt | strip_html | strip_newlines | truncate: 140 }}{% else %}{{ site.description }}{% endif %}" />
  {% if page.image %}
  <meta property="og:image" content="{{ page.url | prepend: site.baseurl | prepend: site.url }}{{ page.image.path }}" />
  <meta property="og:image:width" content="{{ page.image.width }}" />
  <meta property="og:image:height" content="{{ page.image.height }}" />
  {% endif %}
  {% if page.is_post %}
  <meta property="og:site_name" content="{{ site.title }}" />
{% endif %}

<img alt="Uma_Musume_Mirai_001" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_001.jpg">

<img alt="Uma_Musume_Mirai_002" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_002.jpg">

<img alt="Uma_Musume_Mirai_003" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_003.jpg">

<img alt="Uma_Musume_Mirai_004" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_004.jpg">

<img alt="Uma_Musume_Mirai_005" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_005.jpg">

<img alt="Uma_Musume_Mirai_006" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_006.jpg">

<img alt="Uma_Musume_Mirai_007" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_007.jpg">

<img alt="Uma_Musume_Mirai_008" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_008.jpg">

<img alt="Uma_Musume_Mirai_009" src="/images/2022-02-04-Uma Musume Mirai/Uma_Musume_Mirai_009.jpg">


