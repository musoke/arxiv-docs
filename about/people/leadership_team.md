---
title: 'Leadership Team'
template: 'docs/team.html'
people:
  jim:
    name: Jim Entwood
    position: Head of Content
    thumbnail: images/jim.jpg
    bio: |
      Jim coordinates the efforts of the volunteer moderators and arXiv administrators on the daily flow of papers and user support and works with the Scientific Director to develop and improve arXiv's operations policies. His background is in volunteer management and website development for research groups, and he holds an M.A. in Leadership Studies.
  alison:
    name: Alison Fromme
    position: Community Engagement Manager
    thumbnail: images/alison.jpg
    bio: |
      Alison leads arXiv's communications and fundraising efforts, including the membership program for academic and research institutions. Alison's background is in science writing, nonprofit fundraising, and teaching. She is a Cornell University alum and holds an M.S. in Zoology from Washington State University.
  shamsi:
    name: Shamsi Brinn
    position: UX Manager
    thumbnail: images/shamsi.jpg
    bio: |
      Shamsi brings the experiences of arXiv’s diverse users to the forefront of organizational planning. Her role includes gathering feedback and testing product experiences with users, disseminating research findings, and using feedback to inform design and development across the arXiv platform. Shamsi holds a B.F.A. in Graphic Design and Photography from Moore College of Art & Design.
  stephanie:
    name: Stephanie Orphan
    position: Program Director
    thumbnail: images/stephanie.jpg
    bio: |
      Stephanie’s role at arXiv spans administrative management, operational oversight, and implementation of arXiv’s short- and long-term strategic goals. She also serves as a liaison between arXiv, its advisors, and the international open access community. In her previous role at Portico, she served as director of content preservation and publisher relations, ensuring ongoing growth and sustainability. She holds an M.S. in library and information science from the University of Illinois at Urbana-Champaign.
  steinn:
    name: Steinn Sigurdsson
    position: Scientific Director
    orcid: https://orcid.org/0000-0002-8187-1144
    twitter: steinly0
    thumbnail: images/steinn.jpg
    bio: |
      Steinn is Professor of Astrophysics at Penn State University. His research interests include astrophysics and related areas, ranging from cosmology, large scale dynamics and black holes, to formation and evolution of planets and the prospects for discovering non-terrestrial life. Steinn holds a Ph.D. in Theoretical Physics from the California Institute of Technology.
  ramin:
    name: Ramin Zabih
    position: Faculty Director
    thumbnail: images/ramin.jpg
    bio: |
      Ramin is a computer science professor at Cornell Tech and president and founder of the Computer Vision Foundation. His research focuses on computer vision and its applications, especially in medical imaging. As arXiv faculty director, Ramin guides arXiv’s strategic vision and technological modernization with input from the global research and scholarly communications communities. He holds a Ph.D. in Computer Science and Mathematics from Stanford University.
  charles:
    name: Charles Frankston
    position: Technical Director
    thumbnail: images/charles.jpg
    bio: |
      Charles is focused on helping ready arXiv for its next 30 years of stable support of open science and will shepherd arXiv's move to the cloud. He brings his wealth of expertise in a wide range of platforms and languages, systems architecture, and deep commitment to data privacy. Charles holds a B.S. in Computer Science and Engineering from the Massachusetts Institute of Technology.

---

arXiv Leadership Team
=====================
$jinja {{ render_columns_open() }} jinja$
$jinja {{ render_person(people.shamsi) }} jinja$
$jinja {{ render_person(people.jim) }} jinja$
$jinja {{ render_columns_closed() }} jinja$
$jinja {{ render_columns_open() }} jinja$
$jinja {{ render_person(people.charles) }} jinja$
$jinja {{ render_person(people.alison) }} jinja$
$jinja {{ render_columns_closed() }} jinja$
$jinja {{ render_columns_open() }} jinja$
$jinja {{ render_person(people.stephanie) }} jinja$
$jinja {{ render_person(people.steinn) }} jinja$
$jinja {{ render_columns_closed() }} jinja$
$jinja {{ render_columns_open() }} jinja$
$jinja {{ render_person(people.ramin) }} jinja$
$jinja {{ render_columns_closed() }} jinja$
