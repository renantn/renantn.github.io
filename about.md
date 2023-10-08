---
layout: about
title: About Me
prog-lang-imgs:
  - name: C/C++
    path: ../assets/img/stack/cpp.svg
  - name: C#
    path: ../assets/img/stack/csharp.svg
  - name: Python
    path: ../assets/img/stack/python.svg
  - name: Typescript
    path: ../assets/img/stack/typescript.svg
  - name: Javascript
    path: ../assets/img/stack/javascript.svg
  - name: Kotlin
    path: ../assets/img/stack/kotlin.svg
  - name: Ruby
    path: ../assets/img/stack/ruby.svg
framework-imgs:
  - name: Ruby on Rails
    path: ../assets/img/stack/rails.svg
  - name: React / React Native
    path: ../assets/img/stack/react.svg
  - name: Angular
    path: ../assets/img/stack/angular.svg
  - name: Flutter
    path: ../assets/img/stack/flutter.svg
cloud-imgs:
  - name: IBM Cloud
    path: ../assets/img/stack/ibm.svg
  - name: Azure
    path: ../assets/img/stack/azure.svg
  - name: AWS
    path: ../assets/img/stack/aws.svg
author: Renan Nakashima
---

<!--author-->

I've always been a curious person. This naturally led me to become interested in areas related to science, technology, engineering, and mathematics (STEM). My passion for computers and games led me to study Computer Engineering at a public university in Brazil.

Delving deep into the world of the computer - one of the most incredible innovations in history - has been a rewarding journey. The ability to create solutions for a variety of challenges motivated me to specialize in software development.

Today, I consider myself an extremely versatile Software Architect. My career has allowed me to develop technical skills in all areas of the software development cycle: requirements gathering, design, implementation, testing, debugging, deployment, and maintenance.

## Background

- **Education:** I hold a _Master's Degree in Electrical and Computer Engineering_, and _Bachelor's Degree in Computer Engineering_, both from _Universidade Tecnológica Federal do Paraná_ - Brazil, where I gained a solid understanding of the inner workings of computers, electronics, and programming languages. My academic journey has provided me with a strong analytical mindset and problem-solving skills.

- **Experience:** Over the past 5 years, I've honed my software engineering expertise through hands-on experience. I've worked on a wide range of projects, from Embedded Software Development to Mobile and Cloud Native Web Apps. Additionally, I had the privilege of serving as a tech lead for two years, overseeing two projects. These experiences have allowed me to develop a wide range of hard and soft skills, in all steps of the SDLC and in different tech stacks.


## Tech Stack

Throughout my career, I've had the privilege of working with a diverse tech stack, which has equipped me with a well-rounded skill set:

### Programming Languages

<ul class="image-list">
  {% for image in page.prog-lang-imgs %}
    <li>
      <img src="{{ image.path }}" alt="{{ image.name }}" width="120" height="120">
      {{ image.name }}
    </li>
  {% endfor %}
</ul>

### Frameworks

<ul class="image-list">
  {% for image in page.framework-imgs %}
    <li>
      <img src="{{ image.path }}" alt="{{ image.name }}" width="120" height="120">
      {{ image.name }}
    </li>
  {% endfor %}
</ul>

### Cloud Platforms
<ul class="image-list">
  {% for image in page.cloud-imgs %}
    <li>
      <img src="{{ image.path }}" alt="{{ image.name }}" width="120" height="120">
      {{ image.name }}
    </li>
  {% endfor %}
</ul>

## Let's Collaborate

I am always open to new challenges and collaboration opportunities. If you'd like to connect, discuss potential projects, or explore how we can work together to innovate and create, please feel free to [reach out!](mailto:renan.nakashima@pipenex.com)