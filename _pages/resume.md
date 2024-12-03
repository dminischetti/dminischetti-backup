---
layout: single
title: "Resume"
permalink: /resume/
author_profile: true
classes: dark-mode
---

# Personal Info
- **Name**: Dominic Minischetti
- **Title**: PHP Backend Engineer
- **Email**: [dominic.minischetti@gmail.com](mailto:dominic.minischetti@gmail.com)
- **Website**: [minischetti.org](https://minischetti.org)

---

# Social Links
- [GitHub](https://github.com/dminischetti) :octocat:
- [LinkedIn](https://www.linkedin.com/in/dminischetti) :briefcase:
- [Twitter](https://twitter.com/dominischetti) :bird:
- [Instagram](https://instagram.com/dminischetti) :camera:
- [Facebook](https://facebook.com/dominic.minischetti) :globe_with_meridians:

---

## About Me
![Profile Image](/images/IMG_1687.JPG){: .align-right}
**Building efficient solutions for real-world problems.**

PHP Backend Engineer with over 5 years of experience in eCommerce, logistics, and web application development. Proven track record in building high-performance systems and optimizing database architectures. Skilled in agile methodologies and dedicated to clean, efficient code and exceptional user experiences.

Currently expanding my expertise in Laravel and modern PHP frameworks to deliver scalable and robust applications.

---

## Professional Experience
{% for item in site.data.resume.professional_experience %}
### {{ item.title }}
**{{ item.sub_title }}**  
{{ item.caption }}  
{{ item.description | newline_to_br }}
{% endfor %}

---

## Education
{% for item in site.data.resume.education %}
### {{ item.title }}
**{{ item.sub_title }}**  
{{ item.caption }}  
{{ item.description | newline_to_br }}
{% endfor %}

---

## Certifications & Additional Courses
{% for item in site.data.resume.certifications %}
### {{ item.title }}
**{{ item.sub_title }}**  
{{ item.caption }}
{% endfor %}

---

## Technical Skills
{{ site.data.resume.technical_skills }}

---

## Soft Skills
{{ site.data.resume.soft_skills }}

---

## Languages
{{ site.data.resume.languages }}
