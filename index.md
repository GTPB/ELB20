---
layout: page
schemadotorg:
  "@context": http://schema.org/
  "@type": CreativeWork
  "genre": TrainingMaterial

  # Course details
       # "name" -> The acronym and extended name of the course, separated by " - "
       # "description" -> Short description of the course
  name: "ELB20 - Entry level Bioinformatics (2020)"
  description: "Training material for entry level course in bioinformatics with a soft introduction to NGS data analysis."

  # Keywords -> Consult EDAM:Topic
  keywords:  ["http://edamontology.org/topic_0091", "http://edamontology.org/topic_3168", ]

  # Audience -> Following Elixir-Tess input
  audience: ["Academia/ Research Institution", "Industry", "Non-Profit Organisation", "Healthcare"]

  # Author info
  author:
    - "@type": Organization
      name: "The Gulbenkian Training Programme in Bioinformatics"
      alternateName: "GTPB"
      sameAs: "gtpb.igc.gulbenkian.pt/bicourses/index.html"

  # predominant type of learning resources
  "learningResourceType": ["presentation", "exercise", "scripts", "handout"]

  # Contributor info
  contributor:
    - "@type": Person
      name: "David P. Judge"      
    - "@type": Person
      name: "Daniel Sobral"
    - "@type": Person
      name: "Pedro Fernandes"

  # License & Language & url
  license: https://creativecommons.org/licenses/by/4.0/
  inLanguage: "en-us"
  url: "https://gtpb.github.io/ELB20/"
---

![](./assets/WPP_domain_alignment.png)

## Course Description

This is an **entry level** course in three parts, aimed at those with a reasonable biological background but no significant experience with bioinformatics.

The course content is designed to show how, by going through guided exercises, a researcher in the bio-medical area can access sequence data and steer his/her analysis to efficiently extract results, checking how credible they are and reason about using them confidently, in a reproducible way.

This course will also provide a soft introduction to Next Generation Sequencing (NGS) data analysis. This part of the course aims at providing basic skills that are needed when one needs to process NGS data, using open source bioinformatics tools.

Thirdly, the course will cover the broad theme of analytical automation, and how it enhances the capacity of researchers by widening the scope of their experiments, comparing results in a large scale and summarising the findings in simple but very reproducible ways.

## Target Audience

Researchers at any level, wishing to investigate how they might begin to exploit the ever expanding abundance of computing and data resources.

## Detailed Program


---

### [Learning objectives](./pages/objectives_prerequesites.md)

### [Instructors](instructors.md)

---

The source for this course webpage is [in github](https://github.com/GTPB/ELB20).

<br/>

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">ELB20</span> by <span xmlns:cc="http://creativecommons.org/ns#" property="cc:attributionName">GTPB</span> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by/4.0/">Creative Commons Attribution 4.0 International License</a>.
