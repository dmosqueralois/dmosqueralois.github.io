---
layout: single
title: ""
permalink: /QConf/
author_profile: false
classes:
  - wide
  - no-top-nav
  - qconf
---

{% include base_path %}

<style>
/* --- Hide top navigation only on this page --- */
.no-top-nav header,
.no-top-nav .masthead,
.no-top-nav .site-header,
.no-top-nav .greedy-nav,
.no-top-nav nav,
.no-top-nav .skip-links {
  display: none !important;
}
.no-top-nav .initial-content,
.no-top-nav .page__inner-wrap {
  padding-top: 0 !important;
  margin-top: 0 !important;
}

/* --- Make this page use the width better (only QConf) --- */
.qconf .page__content,
.qconf .page__inner-wrap {
  max-width: none !important;
}

/* --- Layout system --- */
.qconf-wrap{
  width: 100%;
  max-width: 1400px;   /* increase/decrease if you want */
  margin: 0 auto;
  padding: 0 1rem;
}

.qconf-hero{
  display: grid;
  grid-template-columns: 1.1fr 0.9fr;
  gap: 1.5rem;
  align-items: stretch;
  margin-top: 0.75rem;
  margin-bottom: 1.25rem;
}

.qconf-photo{
  width: 100%;
  height: 100%;
  min-height: 320px;
  object-fit: cover;
  border-radius: 16px;
}

.qconf-subtitle{
  font-style: italic;
  margin-top: 0.25rem;
  margin-bottom: 1rem;
}

.qconf-list{
  margin-top: 0.75rem;
  margin-bottom: 0;
}

.qconf-grid{
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 1.25rem;
  margin: 1.25rem 0;
}

.qconf-card{
  border: 1px solid rgba(0,0,0,0.10);
  border-radius: 16px;
  padding: 1rem 1.1rem;
  background: rgba(0,0,0,0.015);
}

.qconf-card h2{
  margin-top: 0.2rem;
}

/* Responsive: stack columns on phones */
@media (max-width: 900px){
  .qconf-hero{ grid-template-columns: 1fr; }
  .qconf-grid{ grid-template-columns: 1fr; }
  .qconf-photo{ min-height: 260px; }
}
</style>

<div class="qconf-wrap">

  <!-- HERO BLOCK: Title + (right) photo spanning the first section -->
  <div class="qconf-hero">
    <div markdown="1">

# Differential, Algebraic, and Combinatorial Topology

<div class="qconf-subtitle">
A conference honoring the mathematical contributions of Enrique Macías-Virgós, celebrating his 70th birthday.
</div>

<ul class="qconf-list">
  <li>:calendar: <strong>Dates:</strong> May 7–8, 2026.</li>
  <li>:round_pushpin: <strong>Place:</strong> <a href="https://maps.app.goo.gl/WZcd5STTvySawSY76">Faculty of Mathematics (Santiago de Compostela)</a>.</li>
  <li>:memo: <strong>Registration:</strong> <a href="ENLACE">Registration</a> is free (open until 21/04/2026).</li>
</ul>

    </div>

    <!-- Replace quique.jpg with your filename in /images/ -->
    <div>
      <img class="qconf-photo"
           src="/images/fotoQuique.jpeg"
           alt="Enrique Macías-Virgós">
    </div>
  </div>

  <!-- BLOCK ROW 1: left Invited Speakers / right Travel & Stay -->
  <div class="qconf-grid">
    <div class="qconf-card" markdown="1">
## Invited Speakers

*(to be announced)*

- AAA  
- AAA  

The detailed schedule will be posted here soon.
    </div>

    <div class="qconf-card" markdown="1">
## Travel and stay in Santiago de Compostela

### Arriving in Santiago
- :airplane: The airport is 20 minutes from the city, with taxis and buses available to the city center.
- :train: The train station is in the city center.

### Staying in Santiago
There are several hotels within a 3-minute walk from the Faculty and less than a 10-minute walk from the city center:

- [Hotel Exe Peregrino](https://www.eurostarshotels.co.uk/exe-peregrino.html)
- [Eurostars Gran Hotel Santiago](https://www.eurostarshotels.co.uk/eurostars-gran-hotel-santiago.html)
    </div>
  </div>

  <!-- BLOCK ROW 2: left Organizing Committee / right Contact -->
  <div class="qconf-grid">
    <div class="qconf-card" markdown="1">
## Organizing Committee

- Isaac Carcacía-Campos (USC–CITMAga)  
- Ángel Méndez-Vázquez (USC–CITMAga)  
- David Mosquera Lois (UVigo)  
- María José Pereira Sáez (UDC–CITMAga)
    </div>

    <div class="qconf-card" markdown="1">
## Contact

For questions about the conference, registration, or travel logistics:  
**david.mosquera.lois@uvigo.gal**
    </div>
  </div>

</div>
