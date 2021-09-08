---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: PhD Student in Computer Vision
    company: Inria
    company_url: 'https://www.inria.fr/'
    company_logo:
    location: Grenoble, France
    date_start: '2019-10-01'
    date_end: '2022-10-01'
    description: I am working on 3D/4D modeling of dressed humans from images/videos.
        
  - title: Computer Vision Engineer
    company: Wrnch
    company_url: 'https://wrnch.ai/'
    company_logo: 
    location: Montreal, Canada
    date_start: '2018-10-01'
    date_end: '2019-05-01'
    description: I worked on several computer vision applications that use human pose estimation and on a multi-camera platform for 3D markerless motion capture (multi cameras calibration, video feed synchronization, 3D estimation from several 2D poses).
  
  - title: Master Thesis
    company: DORSAL Polytechnique Montreal
    company_url: 'https://www.dorsal.polymtl.ca/fr/'
    company_logo: 
    location: Montreal, Canada
    date_start: '2017-01-01'
    date_end: '2018-08-01'
    description: I developped performance analysis tools for machine learning dataflow applications executing in heterogeneous environments. I focused on the library TensorFlow and its dataflow computation graph. The goal was to develop tools which will help to understand the performance of the applications and to detect limiting elements or bottlenecks. A main aspect was to insure that the available hardware (CPUs and GPUs) is used efficiently.
  
  - title: Intern
    company: Aspic Technologies
    company_url: 'https://www.aspictechnologies.com/'
    company_logo: 
    location: Tourcoing, France
    date_start: '2015-09-01'
    date_end: '2016-02-01'
    description: |2-
        I worked on different projects:
        * Continuous Integration System  Buildbot, Docker, Wakeonlan, scripts Bash.
        * C++ Dévelopment for a license system  C++, CMake, Boost, XML, Client-Server.
        * Smart C++ tools for memory allocations tagging and monitoring.
    
design:
  columns: '2'
---
