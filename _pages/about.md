---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* --- Home page cards (keeps top nav + left sidebar visible) --- */
.home-wrap{
  width: 100%;
  margin: 0;
}

.home-grid{
  display: grid;
  grid-template-columns: repeat(12, minmax(0,1fr));
  gap: 1rem;
  margin: 0.75rem 0 1rem 0;
  align-items: start;
}

.home-card{
  grid-column: span 12;
  border: 1px solid rgba(0,0,0,0.10);
  border-radius: 16px;
  padding: 1rem 1.1rem;
  background: rgba(0,0,0,0.02);
  box-shadow: 0 2px 10px rgba(0,0,0,0.03);
}

.home-card h2{
  margin-top: 0;
  margin-bottom: 0.45rem;
  font-size: 1.15rem;
}

.home-card p{
  margin: 0 0 0.75rem 0;
  text-align: justify;
}

.home-card p:last-child{
  margin-bottom: 0;
}

.home-hero{
  padding: 1.1rem 1.2rem;
}

.home-hero p{
  font-size: 1.03rem;
  line-height: 1.6;
}

.home-highlight{
  border-left: 4px solid rgba(0,0,0,0.20);
  padding-left: 0.9rem;
}

.home-card ul{
  margin: 0.4rem 0 0 1.1rem;
}

.home-card li{
  margin-bottom: 0.35rem;
}

.home-mini{
  font-size: 0.97rem;
  line-height: 1.5;
}

.home-contact{
  background: rgba(0,0,0,0.03);
}

.home-contact strong{
  word-break: break-word;
}

@media (min-width: 900px){
  .span-12{ grid-column: span 12; }
  .span-8{ grid-column: span 8; }
  .span-6{ grid-column: span 6; }
  .span-4{ grid-column: span 4; }
}
</style>

<div class="home-wrap">

  <div class="home-grid">

    <!-- Intro / Hero -->
    <section class="home-card home-hero span-12">
      <h2>About me</h2>
      <p>
        I am an Assistant Professor at the University of Vigo in the Department of Mathematics.
        My research focuses on algebraic topology and its intersection with combinatorial dynamics,
        exploring the interaction between both areas and their applications.
      </p>
    </section>

    <!-- Research lines -->
    <section class="home-card span-8">
      <h2>Research interests</h2>

      <div class="home-highlight">
        <p>
          Specifically, my research revolves around two interconnected main lines.
          On the one hand, I work in Morse Theory (both discrete and differentiable) and investigate
          certain homotopy and homology invariants, such as homotopy distance, topological complexity,
          Lusternik–Schnirelmann (LS) category, or covering type from a more computational approach.
          To this end, I use cellular, simplicial, homological, and dynamical techniques.
        </p>
      </div>

      <p>
        On the other hand, I strive not to limit myself to the study of invariants of spaces and objects,
        but to investigate invariants of maps or morphisms (recovering the original invariants as a particular case)
        to obtain new results about the former and a deeper understanding of the relationships between them.
      </p>
    </section>

    <!-- Current direction / quick box -->
    <section class="home-card span-4">
      <h2>Current direction</h2>
      <p class="home-mini">
        Recently, I have started exploring applications of algebraic topology and combinatorial dynamics
        in information aggregation problems.
      </p>
    </section>

    <!-- Outreach and service -->
    <section class="home-card span-8">
      <h2>Outreach and academic service</h2>
      <p>
        In addition to my research and teaching activities, I have been collaborating in the organization
        of the Galician stage of the Spanish Mathematical Olympiad (OME) since 2018 and in the final Spanish stage in 2019.
        Since 2024, I have been part of the Galician delegation.
      </p>
      <p>
        I also participate in the Estalmat program, serve as a jury member for research initiation awards
        (such as the Stephen Hawking prize), and engage in mathematical outreach events for the general public.
      </p>
    </section>

    <!-- Collaboration / contact -->
    <section class="home-card home-contact span-4">
      <h2>Collaboration</h2>
      <p class="home-mini">
        If you find my research interesting, have a problem or an idea for a project we could collaborate on,
        feel free to contact me.
      </p>
      <p class="home-mini">
        You can also use the navigation bar to explore publications, teaching, talks, and other activities.
      </p>
    </section>

  </div>
</div>
